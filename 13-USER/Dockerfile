FROM python:3.10-alpine

RUN mkdir /app

RUN addgroup -S aditgroup 
RUN adduser -S -D -h /app adituser aditgroup
RUN chown -R adituser:aditgroup /app
USER adituser

COPY app.py .

EXPOSE 8080
CMD ["python", "app.py"]