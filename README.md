# FabricSamples
Power BI Activity Logs data and Power BI Artifact data. Using Python to incrementally load both the data. Activity data always append the api response to the delta table in fabric. For power BI Artifact, depending on if the data is present in the Lakehouse, it can do a full load or incremental load of the data. You may have to replace GUIDs with your lakehouse guids as per the following reference. 
https://www.linkedin.com/pulse/fabric-onelake-adls-gen2-storage-hierarchical-naming-raju-kumar

