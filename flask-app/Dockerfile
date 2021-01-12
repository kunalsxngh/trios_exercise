#Use Python Image
FROM python:latest
# Copy contents into image
 COPY . .
# run pip dependencies
RUN pip install flask SQLAlchemy pymysql Flask-SQLAlchemy
# Expose correct port
EXPOSE 5000
# Create an entrypoint
ENTRYPOINT [ "python3", "app.py" ]

ENV DATABASE_PASSWORD=root