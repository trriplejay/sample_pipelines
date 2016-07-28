# sample_pipelines

i. Make sure your subscription has the `isNewPipeline: true`  
ii. Sync your account (this is required to update gitlab with your subId)  

This branch is set up to purposely trigger two manifest jobs at the same time, which lead into a single deploy job.  If the deploy job is not properly serialized, strange things can happen, so use this to verify serialization.

To fully verify, make sure you have 3 available minions.
