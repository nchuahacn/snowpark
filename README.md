# Python on Snowflake workshop - July 2022

Thanks for joining us for the July 2022 APAC Python on Snowflake Virtual Hands on Labs!

To get started, you'll want to:
1. Download and install Anaconda Python - https://www.anaconda.com/products/distribution. Miniconda should also be fine. 

2. Set up a Snowflake environment that you will be able to create and delete tables in. If you have a Snowflake account, you will want to ensure that you have a database you can create your own schema and objects (including tables, stages, and functions) in. If you do not have a Snowflake account, or you cannot set up the appropriate privileges, please sign up for an account at https://signup.snowflake.com.

3. Make sure you have accepted the terms of agreement for Anaconda in Snowflake as per https://docs.snowflake.com/en/developer-guide/udf/python/udf-python-packages.html#getting-started. You will need ORGADMIN or higher to do this; if you do not have ORGADMIN, you will need to ask your Snowflake administrator to do so for you. In the meantime, feel free to just use a trial environment and accept the terms of agreement there. 

4. Download this repository, either by using Github's zip download option or by cloning it using your local git. If you download the zip, make sure to unzip it!

4. Set up a conda environment using the requirements.yml file in this repository. You can do this by running `conda env create -f requirements.yml` on the machine you install Anaconda on, from the directory you have unzipped/cloned this repository to. Note that we use the default channels in this lab; this is not mandatory but I have not tested by changing the defaults to Forge or similar. 

5. Download and fill in the `secrets_FILL_ME_IN.json` file in this repository, and rename it to `secrets.json`.

That's it - you're ready to go! I haven't uploaded the notebook yet - there will be time at the start of the workshop to download it. 

