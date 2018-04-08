# TestFairy

Welcome to Delete Old Sessions tool. This tool lets you search for and delete sessions older than a specific number of days.

### Installation

```
npm install git+https://git@github.com:testfairy/delete-old-sessions-tool.git
```

### Running

```
node node_modules/delete-old-sessions-tool --endpoint ENDPOINT_ADDRESS --user EMAIL_ADDRESS --api-key API_KEY --days DAYS [--delete]
```

Options:
  - `endpoint`: Server domain where TestFairy is installed (on-premise or private cloud), eg: acme.testfairy.com (REQUIRED)
  - `user`: Email address of a user on TestFairy who will be doing the search and delete, eg: john@acme.com (REQUIRED)
  - `api-key`: API key of the same user, see Account Preferences page in your installation (REQUIRED)
  - `days`: Show sessions older than this number of days, must be greater than 0 (REQUIRED)
  - `delete`: Delete the sessions found. By default, this tool will only list the sessions
  
Note: after a session has been deleted, there is no way to recover it, so please make sure you want to delete the data.

### Support

If you have any questions, please send an email to `support@testfairy.com`.
