[Table of Contents](../Documentation.md)

# Integration Patterns

## Overview

| Pattern     | Type    |  Scenario                                       |
|-------------|---------|-----------------------------------------------|
| Request & Reply | Synchronous | Salesforce invokes a process on a remote system, waits for completion of that process, and then tracks state based on the response from the remote system. |
| Fire & Forget | Asynchronous | Salesforce invokes a process in a remote system but doesn’t wait for completion of the process. Instead, the remote process receives and acknowledges the request and then hands off control back to Salesforce. |
| Batch Data Synchronization | Asynchronous | Data stored in Lightning Platform is created or refreshed to reflect updates from an external system, and when changes from Lightning Platform are sent to an external system. Updates in either direction are done in a batch manner. |
| Remote Call-In | Asynchronous or Synchronous depending on use case | Data stored in Lightning Platform is created, retrieved, updated, or deleted by a remote system. |
| UI Update Based on Data Changes | Asynchronous | The Salesforce user interface must be automatically updated as a result of changes to Salesforce data. |
| Data Virtualization | Synchronous | Salesforce accesses external data in real time. This removes the need to persist data in Salesforce and then reconcile the data between Salesforce and the external system. |