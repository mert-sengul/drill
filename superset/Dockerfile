FROM electroop/bilal-ss:1
# FROM apache/superset
# Switching to root to install the required packages
USER root
# RUN pip install git+https://github.com/JohnOmernik/sqlalchemy-drill.git
RUN pip uninstall --yes sqlalchemy-drill
# ###
RUN pip install git+https://github.com/mert-sengul/sqlalchemy-drill-safe-db-name.git
# Switching back to using the `superset` user
USER superset