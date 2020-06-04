# Troubleshooting

We collect the most common troubleshooting of using oracle for your reference:

> Instance troubleshooting is closely related to the Instance provider that is Cloud Platform, refer to [Cloud Platform Documentation](https://support.websoft9.com/docs/faq/tech-instance.html)

#### How can I use the logs?

You can find the keywords **Failed** or **error** from the logs directory: `/data/logs`

#### oracle service can't start?

1. Use the debug mode of `oracle-server console` and you can see the errors
   ```
   oracle-server console
   ```
2. Search the keywords **Failed** or **error** from logs: */data/logs/oracle-server*

#### Error in Chrome when modify password?

This error is not attribute to oracle server, once you have upgraded you local Chrome, it solved

![chrome error of oracle](https://libs.websoft9.com/Websoft9/DocsPicture/zh/oracle/oracle-chromeerror-websoft9.png)
