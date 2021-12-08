# pipreqsdjango
Minimal django repo to illustrate the following pipreqs issue: https://github.com/bndr/pipreqs/issues/278

Installing the requirements in an empty venv, and then calling `pipreqs ./ --print` doesn't show the `psycopg2==2.8.5` requirement. 
