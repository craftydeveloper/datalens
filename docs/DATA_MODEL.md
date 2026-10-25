# Data model

## Proposed fields

Dataset entries need a source and update time; metrics need a definition and unit; notes should identify their inputs.

The examples are synthetic contract examples and are not loaded automatically. Before changing persistence, inspect the current serialized state and write a migration that preserves user data. Validate imported records and avoid storing credentials.