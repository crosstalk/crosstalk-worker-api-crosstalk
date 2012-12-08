Crosstalk HTTPS API
=============

Crosstalk API Base Url: `https://api.worker.crxtalk.com`

## Accounts

[POST /account](/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-account) - Create new account

[GET /account/:accountName/activate?activationToken=ACTIVATION_TOKEN](/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-account-activate) - Activate account specified by `:accountName`

[POST /account/:accountName/activate](/crosstalk/crosstalk-worker-api-crosstalk/wiki/Post-account-activate) - Activate account specified by `:accountName`

[GET /account/:accountName/available](/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-account-available) - Check if given `:accountName` is available or already taken

## Login/Logout

[POST /login](/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-login) - Login

[POST /logout](/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-logout) - Logout

## Version

[GET /version](/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-version) - Echoes Crosstalk API version

## Workers

[POST /worker](/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-worker) - Upload new worker