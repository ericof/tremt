# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Érico Andrei <ericof@simplesconsultoria.com.br>" \
      org.label-schema.name="tremt-varnish" \
      org.label-schema.description="Treinamento TRE-MT Varnish image." \
      org.label-schema.vendor="Érico Andrei"

COPY etc/varnish.vcl /etc/varnish/default.vcl
