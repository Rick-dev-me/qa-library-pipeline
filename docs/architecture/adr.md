# Architecture Decision Record

ADR-001: Pipeline Architecture

get all raw dat in first and cleanup once we have it

raw data comes in  - into bronze as is - can be used from auditing in later steps
cleaned in silver
gold is read from silver
