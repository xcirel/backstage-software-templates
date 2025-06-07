# Documents for ${{values.app_name}}

This application has two endpoints:
- `/api/v1/info`
- `/api/v1/healthz`

Here you could expand on what each of these endpoints do.

# How to access the app?

Access the src directory and run the app:
`python app.py`

Now, you can access the app by accessing this URL: `${{values.app_name}}-${{values.app_env}}.local/api/v1/healthz`