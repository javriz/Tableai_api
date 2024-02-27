# Tableai_api
###learning Tableau Api

1. Install tableau server client
   ```
   pip install tableaserverclient
   ```

2. Import Tableauserverclient
   ```
   import tableauserverclient as TSC
   ```
3. login
   ```
   tableau_auth = TSC.TableauAuth('email', 'password', 'sitename')
   ```
   ```
   server = TSC.Server('https://10ax.online.tableau.com/',use_server_version=True)
    ```
4. Connect to server
   ```
      import tableauserverclient as TSC

      tableau_auth = TSC.PersonalAccessTokenAuth('token_name', 'token_acess_code', 'site_name')

      server = TSC.Server('https://10ax.online.tableau.com/', use_server_version=True)

```


