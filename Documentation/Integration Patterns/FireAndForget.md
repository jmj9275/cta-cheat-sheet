[Table of Contents](../Documentation.md)

# Fire & Forget

## Description


## Solutions


## Sequence Diagram

![Fire & Forget](../../Images/FireAndForget-SeqDiagram.png)

## Middleware considerations

| Property            | Mandatory | Desirable | Not required |
|---------------------|-----------|-----------|---------|
| Event Handling | | ✅ | |
| Protocol conversion | | ✅ | |
| Translation and transformation | | ✅ | |
| Queuing and buffering | ✅ | | |
| Synchronous transport protocols | | | ✅ |
| Asynchronous transport protocols | ✅ | | |
| Mediation routing | | ✅ | |
| Process choreography and service orchestration | | ✅ | |
| Transactionality (encryption, signing, reliable delivery, transaction management) | ✅ | | |
| Routing | | | ✅ |
| Extract, transform, and load | | | ✅ |
| Long Polling | ✅ (required for platform events) | | |
