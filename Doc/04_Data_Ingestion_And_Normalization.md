4.1 Data Sources

1.Medical records (PDF)

2.Wearable devices

3.Lab reports

5.Manual symptom entries

4.2 Processing Pipeline

1.OCR (if scanned)

2.Medical Named Entity Recognition (NER)

3.Unit normalization

4.Schema mapping

4.3 Structured Representation
{
  "patient_id": "P101",
  "age": 45,
  "conditions": ["hypertension"],
  "medications": ["amlodipine"],
  "allergies": ["penicillin"],
  "lab_results": {
    "LDL": 160,
    "HbA1c": 6.7
  }
}
