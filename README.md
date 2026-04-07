Amazon-S3-Cross-Region-Replication

Overview

This lab demonstrates how to configure Amazon S3 Cross-Region Replication (CRR) to automatically sync data between two geographically 
distant regions (Mumbai and Singapore). CRR is a critical tool for disaster recovery, data redundancy, and meeting compliance requirements
by ensuring a secondary copy of your data exists in a separate AWS region.


 Architecture Components
**Source Bucket (Mumbai): The primary bucket where data is originally uploaded.

**Destination Bucket (Singapore): The replica bucket that automatically receives copies of the data.

**S3 Versioning: A mandatory feature for both buckets that tracks object history and enables replication.

**IAM Role: A service-linked role that grants S3 permission to read from the source and write to the destination.
