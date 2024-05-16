# run-race-predictions-fancy

A little interactive plotly graph to visualize your garmin running race predictions over time

## How to get your data

To get any data from Garmin you have to get a copy of all your data from Garmin. To do this a request must be, after which Garmin will send you a link to download your data.Garmin says the process usually takes 48 hours (upt to 30 days), but personally for me it takes a few minutes to an hour. Here is the [official guide from Garmin](https://support.garmin.com/en-US/?faq=q22kMdCbU23NUT2Wmspz16). The steps are simple:

1. Go to https://www.garmin.com/account/datamanagement/exportdata/
2. Sign In
3. Request Data
4. Wait for the email
5. Download the data

## How to use the script

First prepare the environment by installing the required packages:

```bash
pip install -r requirements.txt
```

The script is a ipython notebook, so you can run it in your favorite environment.
In the script you have to specify the path to the folder where you downloaded your data.

TODO: finish the README