A [Dash example](https://plot.ly/dash/getting-started) deployed to AWS Lambda and API Gateway using [Zappa](https://github.com/Miserlou/Zappa)

Modify the zappa_settings.json so it points to your bucket

```bash
virtualenv -p ($which python3) env
source env/bin/activate
pip install -r requirements.txt
zappa deploy
```

Status: follow the progress on these issues: 
    [Dash #22](https://github.com/plotly/dash/issues/22) and
    [zappa_dash #2](https://github.com/mcrowson/zappa_dash/issues/2)