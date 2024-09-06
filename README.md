Run with:

gunicorn -k uvicorn.workers.UvicornWorker example.asgi:application --bind :8899

