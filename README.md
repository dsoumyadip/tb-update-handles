# tb-update-handles

This cloud function updates the list of handles to track. It fetches list of handles from flat file stored in Cloud
Storage. Then it makes api call to Twitter API endpoint to get the latest info about handles.

* **Scheduling**:  
  This function is invoked by Cloud Scheduler, scheduled once every day.

