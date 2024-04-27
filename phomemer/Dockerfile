ARG BUILD_FROM
FROM $BUILD_FROM

ENV PHOMEMO_BT_MAC ${PHOMEMO_BT_MAC}

CMD /app/.venv/bin/gunicorn -w 1 'phomeme:app' -b [::0]:8001
