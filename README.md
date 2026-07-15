# Test_Repo

```
"Why did you choose Neo4j instead of Azure SQL?"
Answer: "Azure SQL can certainly answer this question using multiple JOINs. However, as the healthcare data model grows—with patients, encounters, diagnoses, medications, physicians, procedures, radiology reports, lab results, ICU transfers, allergies, and follow-ups—the number of relationships increases significantly.

Neo4j models these relationships directly as nodes and edges, so traversing complex clinical pathways becomes simpler, more intuitive, and often more efficient than maintaining increasingly complex JOIN queries."
```

```
Those are fundamentally time-series and relational data tasks, which Azure SQL handles very well.
```

```
### key challanges
Extract timestamps from different reports.
Use the sample collection time, not the report generation time, for lab values.
Align irregular lab results with continuous vital signs.
Carry the latest lab value forward until a new sample is collected.
Produce a single chronological table that AI can reason over.
```
