<a href="https://github.com/WhiteHat-Data-Science/Data-Webinars/blob/master/images/whitehat.png?raw=true">
  <img src="https://github.com/WhiteHat-Data-Science/Data-Webinars/blob/master/images/whitehat.png?raw=true" />
</a>

## Pre requisite for the webinar
Basic knowledge requirements would be:

* Any experience with SQL
* And/or experience in data analysis

## Session recording
Topic: Transform data using DBT
Date: May 22, 2020 12:53 PM London

Meeting Recording:
https://zoom.us/rec/share/1cpVDOjdpkNOAavK7GeYXO08Ha34eaa8hyAY8_oPyUbDkDUEjzAW74PnF6ZG9eJF

Access Password: 7y+8x$e1

## Introduction:

**[dbt](https://www.getdbt.com/)** (data build tool) enables data analysts and engineers to transform their data using the same practices that software engineers use to build applications.

dbt is the T in ELT. Organize, cleanse, denormalize, filter, rename, and pre-aggregate the raw data in your warehouse so that it's ready for analysis.

![dbt architecture](https://github.com/WhiteHat-Data-Science/Data-Webinars/blob/master/images/dbt-arch.png?raw=true)

dbt can be used to [aggregate pageviews into sessions](https://github.com/fishtown-analytics/snowplow), calculate [ad spend ROI](https://github.com/fishtown-analytics/facebook-ads), or report on [email campaign performance](https://github.com/fishtown-analytics/mailchimp).

## Understanding dbt

Analysts using dbt can transform their data by simply writing select statements, while dbt handles turning these statements into tables and views in a data warehouse.

These select statements, or "models", form a dbt project. Models frequently build on top of one another – dbt makes it easy to [manage relationships](https://docs.getdbt.com/docs/ref) between models, and [visualize these relationships](https://docs.getdbt.com/docs/documentation), as well as assure the quality of your transformations through [testing](https://docs.getdbt.com/docs/testing).

![dbt dag](https://github.com/WhiteHat-Data-Science/Data-Webinars/blob/master/images/dbt-dag.png?raw=true)

## Getting started

-   [Install dbt](https://docs.getdbt.com/docs/installation)
-   Read the [documentation](https://docs.getdbt.com/).
-   Productionize your dbt project with [dbt Cloud](https://www.getdbt.com)

## Find out more

-   Check out the [Introduction to dbt](https://docs.getdbt.com/docs/introduction/).
-   Read the [dbt Viewpoint](https://docs.getdbt.com/docs/about/viewpoint/).
