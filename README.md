<a href="https://githubsfdeploy.herokuapp.com?owner=praween546&repo=CPQQuickStart&ref=master">
  <img alt="Deploy to Salesforce"
       src="https://raw.githubusercontent.com/afawcett/githubsfdeploy/master/deploy.png">
</a>

# CPQ ORG Quick Setup

1. [Install](https://install.steelbrick.com/) CPQ and Billing Package
2. Setup > Feed Tracking > Enable Feed Tracking for CPQ Quote Object.
2. Deploy Package from GIT
4. Modify SBQQ__LineEditor Field Set on SBQQ__Quote__c object to add the fields you need to be displayed for quick quote creation.
4. Add Quick Quote Lightning Action to Account Layout
