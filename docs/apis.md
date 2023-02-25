# APIs

## Admin API
+ [ ] **Fetch settings** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#fetch-settings) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/admin/settings`
+ [ ] **Update settings** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#update-settings) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/admin/settings`
+ [ ] **Grafana stats** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#grafana-stats) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/admin/stats`
+ [ ] **Grafana usage report preview** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#grafana-usage-report-preview) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/admin/usage-report-preview`
+ [ ] **Global users** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#global-users) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/users`
+ [ ] **Password for user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#password-for-user) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/admin/users/:id/password`
+ [ ] **Permissions** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#permissions) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/admin/users/:id/permissions`
+ [ ] **Delete global user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#delete-global-user) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/admin/users/:id`
+ [ ] **Pause all alerts** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#pause-all-alerts) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/pause-all-alerts`
+ [ ] **Auth tokens for user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#auth-tokens-for-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/admin/users/:id/auth-tokens`
+ [ ] **Revoke auth token for user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#revoke-auth-token-for-user) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/users/:id/revoke-auth-token`
+ [ ] **Logout user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#logout-user) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/users/:id/logout`
+ [ ] **Reload dashboard provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/dashboards/reload`
+ [ ] **Reload datasource provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/datasources/reload`
+ [ ] **Reload plugins provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/plugins/reload`
+ [ ] **Reload notification provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/notifications/reload`
+ [ ] **Reload access control provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/access-control/reload`
+ [ ] **Reload alert provisioning** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-provisioning-configurations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/provisioning/alerting/reload`
+ [ ] **Reload LDAP configuration** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#reload-ldap-configuration) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/ldap/reload`
+ [ ] **Rotate data encryption keys** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#rotate-data-encryption-keys) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/encryption/rotate-data-keys`
+ [ ] **Re-encrypt data encryption keys** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#re-encrypt-data-encryption-keys) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/encryption/reencrypt-data-keys`
+ [ ] **Re-encrypt secrets** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#re-encrypt-secrets) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/encryption/reencrypt-secrets`
+ [ ] **Roll back secrets** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/admin/#roll-back-secrets) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/admin/encryption/rollback-secrets`

## Alerting provisioning API
+ [ ] **Get rule by UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-alert-rule) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/alert-rules/{UID}`
+ [ ] **Create new alert rule** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-post-alert-rule) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/v1/provisioning/alert-rules`
+ [ ] **Update an existing rule** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-alert-rule) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/alert-rules/{UID}`
+ [ ] **Update the interval of rule group** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-alert-rule-group) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/folder/{FolderUID}/rule-groups/{Group}`
+ [ ] **Delete a specified alert rule by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-delete-alert-rule) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/v1/provisioning/alert-rules/{UID}`
+ [ ] **Get all contact points** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-contactpoints) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/contact-points`
+ [ ] **Create a contact point** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-post-contactpoints) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/v1/provisioning/contact-points`
+ [ ] **Update an existing contact point** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-contactpoint) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/contact-points/{UID}`
+ [ ] **Delete a contact point** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-delete-contactpoints) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/v1/provisioning/contact-points/{UID}`
+ [ ] **Get notification policy tree** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-policy-tree) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/policies`
+ [ ] **Set notification policy tree** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-policy-tree) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/policies`
+ [ ] **Get all mute timings** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-mute-timings) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/mute-timings`
+ [ ] **Get a mute timing** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-mute-timing) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/mute-timings/{name}`
+ [ ] **Create a new mute timing** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-post-mute-timing) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/v1/provisioning/mute-timings`
+ [ ] **Replace an existing mute timing** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-mute-timing) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/mute-timings/{name}`
+ [ ] **Delete a mute timing** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-delete-mute-timing) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/v1/provisioning/mute-timings/{name}`
+ [ ] **Get all message templates** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-templates) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/templates`
+ [ ] **Get a message template** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-get-template) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/v1/provisioning/templates/{name}`
+ [ ] **Create or update a template** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-put-template) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/v1/provisioning/templates/{name}`
+ [ ] **Delete a template** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/alerting_provisioning/#route-delete-template) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/v1/provisioning/templates/{name}`

## Annotations API
+ [ ] **Find annotations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#find-annotations) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/annotations`
+ [ ] **Create annotations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#create-annotation) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/annotations`
+ [ ] **Create annotations in Graphite format** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#create-annotation-in-graphite-format) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/annotations/graphite`
+ [ ] **Update annotation** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#update-annotation) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/annotations/:id`
+ [ ] **Patch annotation** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#patch-annotation) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/annotations/:id`
+ [ ] **Delete annotation by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#delete-annotation-by-id) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/annotations/:id`
+ [ ] **Find annotations tags** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/annotations/#find-annotations-tags) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/annotations/tags`

## Authentication API

+ [ ] **Auth HTTP resources / actions** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/auth/#auth-http-resources--actions) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/auth/keys`
+ [ ] **Api Keys** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/auth/#api-keys) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/auth/keys`
+ [ ] **Create API Key** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/auth/#create-api-key) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/auth/keys`
+ [ ] **Delete API Key** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/auth/#delete-api-key) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/auth/keys/:id`

## Correlations API

+ [ ] **Create correlations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#create-correlations) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/datasources/uid/:sourceUID/correlations`
+ [ ] **Delete correlations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#delete-correlations) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/datasources/uid/:sourceUID/correlations/:correlationUID`
+ [ ] **Update correlations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#update-correlations) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/datasources/uid/:sourceUID/correlations/:correlationUID`
+ [ ] **Get single correlation** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#get-single-correlation) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/uid/:sourceUID/correlations/:correlationUID`
+ [ ] **Get all correlations originating from a given data source** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#get-all-correlations-originating-from-a-given-data-source) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/uid/:sourceUID/correlations`
+ [ ] **Get all correlations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/correlations/#get-all-correlations) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/correlations`

## Dashboard API

+ [ ] **Create / Update dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard/#create--update-dashboard) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/db`
+ [ ] **Get dashboard by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard/#get-dashboard-by-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/uid/:uid`
+ [ ] **Delete dashboard by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard/#delete-dashboard-by-uid) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/dashboards/uid/:uid`
+ [ ] **Gets the home dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard/#gets-the-home-dashboard) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/home`
+ [ ] **Tags for Dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard/#tags-for-dashboard) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/tags`

## Dashboard Permissions API

+ [ ] **Get permissions for a dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_permissions/#get-permissions-for-a-dashboard) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/uid/:uid/permissions`
+ [ ] **Update permissions for a dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_permissions/#update-permissions-for-a-dashboard) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/uid/:uid/permissions`
+ [ ] **Get permissions for a dashboard by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_permissions/#get-permissions-for-a-dashboard-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/id/:dashboardId/permissions`
+ [ ] **Update permissions for a dashboard by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_permissions/#update-permissions-for-a-dashboard-by-id) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/id/:dashboardId/permissions`

## Dashboard Versions API

+ [ ] **Get all dashboard versions** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#get-all-dashboard-versions) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/id/:dashboardId/versions`
+ [ ] **Get all dashboard versions by dashboard UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#get-all-dashboard-versions-by-dashboard-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/uid/:uid/versions`
+ [ ] **Get dashboard version** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#get-dashboard-version) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/id/:dashboardId/versions/:version`
+ [ ] **Get dashboard version by dashboard UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#get-dashboard-version-by-dashboard-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboards/uid/:uid/versions/:version`
+ [ ] **Restore dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#restore-dashboard) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/id/:dashboardId/restore`
+ [ ] **Restore dashboard by dashboard UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#restore-dashboard-by-dashboard-uid) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/uid/:uid/restore`
+ [ ] **Compare dashboard versions** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/dashboard_versions/#compare-dashboard-versions) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/dashboards/calculate-diff`

## Data source API

+ [ ] **Data source API** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#data-source-api) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources`
+ [ ] **Get all data sources** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#get-all-data-sources) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources`
+ [ ] **Get a single data source by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#get-a-single-data-source-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/:datasourceId`
+ [ ] **Get a single data source by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#get-a-single-data-source-by-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/uid/:uid`
+ [ ] **Get a single data source by name** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#get-a-single-data-source-by-name) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/name/:name`
+ [ ] **Get data source Id by name** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#get-data-source-id-by-name) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/id/:name`
+ [ ] **Create a data source** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#create-a-data-source) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/datasources`
+ [ ] **Update an existing data source by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#update-an-existing-data-source-by-id) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/datasources/:datasourceId`
+ [ ] **Update an existing data source** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#update-an-existing-data-source) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/datasources/uid/:uid`
+ [ ] **Delete an existing data source by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#delete-an-existing-data-source-by-id) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/datasources/:datasourceId`
+ [ ] **Delete an existing data source by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#delete-an-existing-data-source-by-uid) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/datasources/uid/:uid`
+ [ ] **Delete an existing data source by name** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#delete-an-existing-data-source-by-name) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/datasources/name/:datasourceName`
+ [ ] **Data source proxy calls by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#data-source-proxy-calls-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/proxy/:datasourceId/*`
+ [ ] **Data source proxy calls** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#data-source-proxy-calls) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/proxy/uid/:uid/*`
+ [ ] **Check data source health by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#check-data-source-health-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/:datasourceId/health`
+ [ ] **Check data source health** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#check-data-source-health) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/uid/:uid/health`
+ [ ] **Fetch data source resources by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#fetch-data-source-resources-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/:datasourceId/resources/*`
+ [ ] **Fetch data source resources** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/data_source/#fetch-data-source-resources) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/datasources/uid/:uid/resources/*`

## Folder API

+ [ ] **Get all folders** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#get-all-folders) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/folders`
+ [ ] **Get folder by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#get-folder-by-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/folders/:uid`
+ [ ] **Create folder** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#create-folder) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/folders`
+ [ ] **Update folder** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#update-folder) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/folders/:uid`
+ [ ] **Delete folder** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#delete-folder) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/folders/:uid`
+ [ ] **Get folder by id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder/#get-folder-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/folders/id/:id`

## Folder Permissions API

+ [ ] **Get permissions for a folder** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder_permissions/#get-permissions-for-a-folder) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/folders/:uid/permissions`
+ [ ] **Update permissions for a folder** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder_permissions/#update-permissions-for-a-folder) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/folders/:uid/permissions`

## Folder / Dashboard Search API

+ [ ] **Search folders and dashboards** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/folder_dashboard_search/#search-folders-and-dashboards) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/search/

## Library Element API

+ [ ] **Get all library elements** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#get-all-library-elements) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/library-elements`
+ [ ] **Get library element by uid** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#get-library-element-by-uid) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/library-elements/:uid`
+ [ ] **Get library element by name** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#get-library-element-by-name) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/library-elements/name/:name`
+ [ ] **Get library element connections** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#get-library-element-connections) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/library-elements/:uid/connections`
+ [ ] **Create library element** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#create-library-element) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/library-elements`
+ [ ] **Update library element** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#update-library-element) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/library-elements/:uid`
+ [ ] **Delete library element** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/library_element/#delete-library-element) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/library-elements/:uid`

## Organization API

+ [ ] **Get current Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-current-organization) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/org/`
+ [ ] **Get all users within the current organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-all-users-within-the-current-organization) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/org/users`
+ [ ] **Get all users within the current organization (lookup)** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-all-users-within-the-current-organization-lookup) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/org/users/lookup`
+ [ ] **Updates the given user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#updates-the-given-user) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/org/users/:userId`
+ [ ] **Delete user in current organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#delete-user-in-current-organization) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/org/users/:userId`
+ [ ] **Update current Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#update-current-organization) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/org`
+ [ ] **Add a new user to the current organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#add-a-new-user-to-the-current-organization) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/org/users`
+ [ ] **Get Organization by Id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-organization-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/orgs/:orgId`
+ [ ] **Get Organization by Name** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-organization-by-name) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/orgs/name/:orgName`
+ [ ] **Create Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#create-organization) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/orgs`
+ [ ] **Search all Organizations** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#search-all-organizations) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/orgs?perpage=10&page=1`
+ [ ] **Update Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#update-organization) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/orgs/:orgId`
+ [ ] **Delete Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#delete-organization) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/orgs/:orgId`
+ [ ] **Get Users in Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#get-users-in-organization) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/orgs/:orgId/users`
+ [ ] **Add User in Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#add-user-in-organization) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/orgs/:orgId/users`
+ [ ] **Update Users in Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#update-users-in-organization) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/orgs/:orgId/users/:userId`
+ [ ] **Delete User in Organization** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/org/#delete-user-in-organization) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/orgs/:orgId/users/:userId`

## Other API

+ [ ] **Get Settings** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/other/#get-settings) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/frontend/settings`
+ [ ] **Renew session based on remember cookie** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/other/#renew-session-based-on-remember-cookie) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/login/ping`
+ [ ] **Returns health information about Grafana** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/other/#returns-health-information-about-grafana) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/health`

## Playlists API

+ [ ] **Search Playlist** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#search-playlist) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/playlists`
+ [ ] **Get one playlist** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#get-one-playlist) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/playlists/:uid`
+ [ ] **Get Playlist items** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#get-playlist-items) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/playlists/:uid/items`
+ [ ] **Get Playlist dashboards** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#get-playlist-dashboards) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/playlists/:uid/dashboards`
+ [ ] **Create a playlist** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#create-a-playlist) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/playlists/`
+ [ ] **Update a playlist** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#update-a-playlist) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/playlists/:uid`
+ [ ] **Delete a playlist** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/playlist/#delete-a-playlist) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/playlists/:uid`

## Preferences API

+ [ ] **Get Current User Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#get-current-user-prefs) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user/preferences`
+ [ ] **Update Current User Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#update-current-user-prefs) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/user/preferences`
+ [ ] **Patch Current User Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#patch-current-user-prefs) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/user/preferences`
+ [ ] **Get Current Org Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#get-current-org-prefs) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/org/preferences`
+ [ ] **Update Current Org Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#update-current-org-prefs) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/org/preferences`
+ [ ] **Patch Current Org Prefs** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/preferences/#patch-current-org-prefs) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/org/preferences`

## Short URL API

+ [ ] **Create short URL** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/short_url/#create-short-url) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/short-urls`

## Query history API

+ [ ] **Add query to Query history** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#add-query-to-query-history) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/query-history`
+ [ ] **Query history search** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#query-history-search) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/query-history`
+ [ ] **Delete query from Query history by UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#delete-query-from-query-history-by-uid) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/query-history/:uid`
+ [ ] **Update comment of query in Query history by UID** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#update-comment-of-query-in-query-history-by-uid) :octicons-dot-fill-16: **PATCH** :octicons-dot-fill-16: `/api/query-history/:uid`
+ [ ] **Star query in Query history** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#star-query-in-query-history) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/query-history/star/:uid`
+ [ ] **Unstar query in Query history** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#unstar-query-in-query-history) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/query-history/star/:uid`
+ [ ] **Migrate queries to Query history** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/query_history/#migrate-queries-to-query-history) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/query-history/migrate`

## Snapshot API

+ [ ] **Create new snapshot** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/snapshot/#create-new-snapshot) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/snapshots`
+ [ ] **Get list of Snapshots** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/snapshot/#get-list-of-snapshots) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/dashboard/snapshots`
+ [ ] **Get Snapshot by Key** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/snapshot/#get-snapshot-by-key) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/snapshots/:key`
+ [ ] **Delete Snapshot by Key** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/snapshot/#delete-snapshot-by-key) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/snapshots/:key`
+ [ ] **Delete Snapshot by deleteKey** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/snapshot/#delete-snapshot-by-deletekey) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/snapshots-delete/:deleteKey`

## Team API

+ [ ] **Team Search With Paging** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#team-search-with-paging) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/teams/search?perpage=50&page=1&query=myteam`
+ [ ] **Get Team By Id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#get-team-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/teams/:id`
+ [ ] **Delete Team By Id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#delete-team-by-id) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/teams/:id`
+ [ ] **Get Team Members** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#get-team-members) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/teams/:teamId/members`
+ [ ] **Add Team Member** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#add-team-member) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/teams/:teamId/members`
+ [ ] **Remove Member From Team** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#remove-member-from-team) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/teams/:teamId/members/:userId`
+ [ ] **Get Team Preferences** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#get-team-preferences) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/teams/:teamId/preferences`
+ [ ] **Update Team Preferences** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/team/#update-team-preferences) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/teams/:teamId/preferences`

## User API

+ [ ] **Search Users** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#search-users) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users?perpage=10&page=1`
+ [ ] **Search Users with Paging** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#search-users-with-paging) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users/search?perpage=10&page=1&query=mygraf`
+ [ ] **Get single user by Id** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#get-single-user-by-id) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users/:id`
+ [ ] **Get single user by Username(login) or Email** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#get-single-user-by-usernamelogin-or-email) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users/lookup?loginOrEmail=user@mygraf.com`
+ [ ] **User Update** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#user-update) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/users/:id`
+ [ ] **Get Organizations for user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#get-organizations-for-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users/:id/orgs`
+ [ ] **Get Teams for user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#get-teams-for-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/users/:id/teams`
+ [ ] **User** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user`
+ [ ] **Actual User** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#actual-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user`
+ [ ] **Change Password** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#change-password) :octicons-dot-fill-16: **PUT** :octicons-dot-fill-16: `/api/user/password`
+ [ ] **Switch user context for a specified user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#switch-user-context-for-a-specified-user) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/users/:userId/using/:organizationId`
+ [ ] **Switch user context for signed in user** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#switch-user-context-for-signed-in-user) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/user/using/:organizationId`
+ [ ] **Organizations of the actual User** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#organizations-of-the-actual-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user/orgs`
+ [ ] **Teams that the actual User is member of** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#teams-that-the-actual-user-is-member-of) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user/teams`
+ [ ] **Star a dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#star-a-dashboard) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/user/stars/dashboard/:dashboardId`
+ [ ] **Unstar a dashboard** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#unstar-a-dashboard) :octicons-dot-fill-16: **DELETE** :octicons-dot-fill-16: `/api/user/stars/dashboard/:dashboardId`
+ [ ] **Auth tokens of the actual User** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#auth-tokens-of-the-actual-user) :octicons-dot-fill-16: **GET** :octicons-dot-fill-16: `/api/user/auth-tokens`
+ [ ] **Revoke an auth token of the actual User** [:material-link:](https://grafana.com/docs/grafana/latest/developers/http_api/user/#revoke-an-auth-token-of-the-actual-user) :octicons-dot-fill-16: **POST** :octicons-dot-fill-16: `/api/user/revoke-auth-token`
