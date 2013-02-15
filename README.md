Crosstalk HTTPS API
=============

Crosstalk API Base Url: `https://api.worker.crxtalk.com`

## Accounts

[POST /account](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-account) - Create new account

[GET /account/:accountName/activate?activationToken=ACTIVATION_TOKEN](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-account-activate) - Activate account specified by `:accountName`

[POST /account/:accountName/activate](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/Post-account-activate) - Activate account specified by `:accountName`

[GET /account/:accountName/available](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-account-available) - Check if given `:accountName` is available or already taken

## Login/Logout

[POST /login](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-login) - Login

[POST /logout](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-logout) - Logout

## Version

[GET /version](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/GET-version) - Echoes Crosstalk API version

## Workers

[POST /worker](https://github.com/crosstalk/crosstalk-worker-api-crosstalk/wiki/POST-worker) - Upload new worker
