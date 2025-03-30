# Data_Architecture
Collection of different data architectures for various use cases
I will try to outline in simple block diagrams data architecture for various use cases, such as:

1. Batch Data Pipelines
2. Streaming Data Pipelines
3. Analytical Data Architecture for Data Lake/Data Warehouse
4. Operation Data Architecture

I will try to include more use cases as we proceed. Contributions and comments are welcome!!

1. DA_Operations_N_Analytics:
   This simple data architecture collates data from different source systems:
     Application Data
     Databases
     Real Time Data (IoT etc.)
  Ingests data and performs transformations for the data to be used by both:
      Operational Use cases
      Analytics Use cases
  It is a simplified and indicative data model providing high level view of target system architecture and does not delve deep into implementation.
  Also, I have considered Google Cloud to be cloud provider for this architectural implementation

