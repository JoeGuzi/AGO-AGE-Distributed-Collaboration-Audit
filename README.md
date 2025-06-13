Description: AGO AGE Distributed Collaboration Audit is used to audit collaborations configured in the connected AGO or AGE Organization. The Audit gathers basic information about the distributed collaboration, and it also audits the sync history for the configured collaborations.

Created on: 6/12/25

Purpose: The purpose of this notebook is to gather basic information about the distributed collaboration, and it also audits the sync history for the configured collaborations. Follow the steps outlined below. You can connect to AGO or AGE, and the notebook will audit the collaborations configured for the connected AGO or AGE organization. The notebook prompts the user for a folder to save excel files of the results. To audit the sync history, you define a date range, and the notebook will return records showing information about the attempts to synchronize the collaboration over that date range. There is a limit of 10 records, so it will return the most recent 10 records if the collaboration was synchronized more than 10 times over that date range. If a date range is not defined the sync history will not be audited. The results are displayed in a pandas data frame and exported to excel. You can optionally upload the collaboration audit to AGO or AGE.

Authored By: Joe Guzi

Previous Production Date:

Production Date: 6/12/25

Notes: AGO, AGE, Collaboration
