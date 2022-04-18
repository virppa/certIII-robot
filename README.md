# Robocorp Certificate level III robot
This robot is split into producer and consumer processes:
- Producer fetches, filters and sorts raw .CSV to separate work items.
- Consumer handles work item data validation, POST requests and exception handling.
  - Failed work items are separated from the succesfull ones
  - Can be manually retried 

## Learning materials
https://robocorp.com/docs/courses/work-data-management
