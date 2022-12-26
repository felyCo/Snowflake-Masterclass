
# Architecture

-SnowflakeDB Separates the control planes for maximum control and scalability
Snowflake Architecture consist ofthree layers namely;
- Cloud Services  >> Managing infrastructure, Access control, security, optimizer and metadata
- Querry Processing  >> This is where MMP(Massive Parallel Processing). This is the muscle of the system. Provides several virtual computer resouce to process the all the querries and all the operations.
- Storage  >> This is where data is stored. This is done in an Hybrid Columnar Storage and saved in blobs that is convenient for Big Data Analytics and Quierrying and minimizes the expensive input output request(I/O)


At a high level, key summary of hybrid-columnar:

   - Horizontal and vertical partitioning
   - Automatic column level and partition level compression
   - Natural (built-in) data clustering based on ingestion date (order)

    Blob >>> Blob storage is a type of cloud storage for unstructured data. A "blob," which is short for Binary Large Object, is a mass of data in binary form that does     not necessarily conform to any file format. Blob storage keeps these masses of data in non-hierarchical storage areas called data lakes.
    The data is compressed into blobs and fetched as blobs.

![Felix Checkin](https://user-images.githubusercontent.com/32365871/209571773-9674f529-2aa5-46b2-abe0-55456897e873.jpg)      ![Felix Checkin (1)](https://user-images.githubusercontent.com/32365871/209574111-5a7867cf-adb8-4e69-81bf-5f46dfc2aba7.jpg)

