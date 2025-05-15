```markdown
# Grafana Setup Guide

1. Open Grafana UI
```

[http://localhost:5000](http://localhost:5000)

```

2. Log in with the default credentials:
- **Username:** `admin`
- **Password:** `admin`

3. When prompted, create and confirm a new **admin** password.

4. Navigate to **Configuration** → **Data Sources**.

5. Click **Add data source**, then select **Prometheus**.

6. In the **HTTP** section, set the **URL** to:
```

[http://prometheus:9090](http://prometheus:9090)

```

7. Click **Save & Test** to verify the connection.

8. Go to **Dashboards** → **Manage** → **Import**.

9. In the **Import via Grafana.com** field, enter:
```

893

```

10. Under **Prometheus**, ensure the data source is set to **Prometheus**.

11. Click **Import** to load the Docker monitoring dashboard.
```
