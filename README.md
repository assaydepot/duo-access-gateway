Duo Access Gateway Helm Chart
---

Duo doesn't officially support kubernetes but they do provide a basic docker-compose manifest. The manifest has been converted in to a relatively full featured and opinionated helm chart.

How to use
---

    git clone git@github.com:assaydepot/duo-access-gateway.git
    helm -n duo upgrade --install dag .
