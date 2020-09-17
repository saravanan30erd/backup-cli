# backup-cli
Bash cli with various backup functionalities

config.template should be copied into config file, where we should update the details.

steps
-------

    # Run the Jira backup [take backup in local filesystem]
    ./backup-cli jira local 
    
    # Run the Jira backup [store backup in Azure blob]
    ./backup-cli jira azure
    
    # Run the Gitlab backup [store backup in Azure blob]
    ./backup-cli gitlab azure
