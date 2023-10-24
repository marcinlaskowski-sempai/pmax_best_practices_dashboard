# pMaximizer (Formally pMax Best Practices Dashboard)

  

## Problem Statement

  

Reporting for pMax campaigns is cumbersome and advertisers need a simple way to see an overview of their accounts and get a clear picture of their assets's performance in their pmax campaigns.

  

## Solution

pMaximizer is a best practice dashboard that provides a centralized monitoring of the pMax campaigns' performance and the assets uploaded. Built in Looker Studio, It helps clearly identify if the campaigns and assets comply with the best practice guidelines and gives actionable insights to enhance asset groups' and feed quality.

Moreover, assets' performance is displayed and conveniently presented so advertisers can refresh poorly performing assets.



## Deliverable (Implementation)

  
* LookerStudio dashboard based on your Google Ads and Merchant Center data.

  

## Prerequisites

1. Join [this group](https://groups.google.com/g/pmax-dashboard-template-readers/)


1. Obtain a Developer token

	a. This can be found in [Google Ads](ads.google.com) on the MCC level

	b. Go to Tools & Settings > Setup > API Center. If you do not see a developer token there, please complete the details and request one.

	c. By default, your access level is 'Test Account'; please apply for 'Basic access' if you don't have it. Follow [these instructions](https://developers.google.com/google-ads/api/docs/access-levels)

  

1. Create a new Google Cloud Project on the [Google Cloud Console](https://console.cloud.google.com/), **make sure it is connected to a billing account**

  

### Installation

  

Click on the blue Deploy button and follow the instructions:

 [![text](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSCDIyJjIDWlJHd_x6RAaKczT5_9yc_IC3voZoSUgPwZ9Qn2gQRI3-e_Ra9UR2zEgMVMBM&usqp=CAU)](https://console.cloud.google.com/?cloudshell=true&cloudshell_git_repo=https://github.com/google/pmax_best_practices_dashboard&cloudshell_tutorial=walkthrough.md)

### Usage

In order to update the code execute the following commands in your Cloud Shell:

```
cd pmax_best_practices_dashboard
git pull
./deploy-scripts.sh
```

The following morning the changes will go into effect.

If you would like to run the updated code right away, execute:
```
./run-wf.sh
```

## Disclaimer

** This is not an officially supported Google product.**

Copyright 2021 Google LLC. This solution, including any related sample code or data, is made available on an “as is,” “as available,” and “with all faults” basis, solely for illustrative purposes, and without warranty or representation of any kind. This solution is experimental, unsupported and provided solely for your convenience. Your use of it is subject to your agreements with Google, as applicable, and may constitute a beta feature as defined under those agreements. To the extent that you make any data available to Google in connection with your use of the solution, you represent and warrant that you have all necessary and appropriate rights, consents and permissions to permit Google to use and process that data. By using any portion of this solution, you acknowledge, assume and accept all risks, known and unknown, associated with its usage, including with respect to your deployment of any portion of this solution in your systems, or usage in connection with your business, if at all.
