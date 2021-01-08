#Use Python Image
FROM python:3.7
# Install apt dependencies
 RUN apt install update
# Copy contents into image
 COPY app.py .
 COPY CreateTable.sql .
# run pip dependencies
RUN pip install -r Flask
RUN pip install sqlAlchemy
# Expose correct port
EXPOSE 80
# Create an entrypoint
ENTRYPOINT [ "python", "app.py" ]
