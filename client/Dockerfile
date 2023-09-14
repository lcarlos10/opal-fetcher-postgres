FROM permitio/opal-client:latest
RUN pip install --no-cache-dir --user opal-fetcher-postgres
##export OPAL_FETCH_PROVIDER_MODULES=opal_common.fetcher.providers,opal_fetcher_postgres.provider
##docker run -it --env OPAL_FETCH_PROVIDER_MODULES -p 7766:7000 -p 8181:8181 opal-client:latest