# Class 01: Arrays and Structs

## Introduction

BigQuery is a powerful serverless database service fully hosted by Google whose main design is to process terabytes of data in the seconds range.

Special emphasis for the *serverless* description: this means that we actually don't have to take any responsability with infrastructure or architectural designs in order to keep the tool up and running. In practice, using it is so simple that anyone can create an account, login for its sandbox environment and start using it right away.

In fact, it's due this simplicity that we started using it as our main database tool and now came up with this quick and dirty tutorial to teach a bit about what we've learned, some cool techniques and share some ideas for you to use in your projects as well.

As BigQuery keeps growing in popularity ([Kaggle](https://www.kaggle.com/dansbecker/getting-started-with-sql-and-bigquery) has already integrated its challenges datasets with BigQuery), knowing how to make good use of the tool can be the difference between success in a project or failure due wasted time on stuff such as infrastructure team and so on.

For what it follows, we'll give a brief view on its architecture. This is not mandatory in order to understand BigQuery and we wrote it more for those who are curiouss! If you want to skip straight to action, please refer to section x.x.

## Architecture

Here, we'll briefly discuss on what is happening behind BigQuery and its internal architecture. Knowing this will help you to understand why we use the tool the way we do and more about its philosophy on processing data (which basically comes from the Dremel architecture).

So to begin with, BigQuery is the integration of the following tools working together: [Colossus](https://cloud.google.com/files/storage_architecture_and_challenges.pdf), [Capacitor](https://cloud.google.com/blog/products/gcp/inside-capacitor-bigquerys-next-generation-columnar-storage-format), [Jupiter](https://cloudplatform.googleblog.com/2015/06/A-Look-Inside-Googles-Data-Center-Networks.html), [Dremel](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/36632.pdf) and [Borg](https://ai.google/research/pubs/pub43438).






