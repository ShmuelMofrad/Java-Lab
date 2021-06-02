# GlassFish Server

## Starting and Stopping the GlassFish Server

**Before You Begin**
GlassFish Server software must be installed before you start the **domain**.
A **domain** is a set of one or more GlassFish Server instances managed by one administration server.

Run the `asadmin start-domain` command without an operand:

```
$ asadmin start-domain --verbose
```

- The GlassFish Server’s port number. The default is 8080.

- The administration server’s port number. The default is 4848.

An **administration user name and password**. The **default user name** is `admin`, and by **default no password** is required.

With no arguments, the `start-domain` command initiates the default domain, which is `domain1`. The `--verbose` flag causes all logging and debugging output to appear on the terminal window or command prompt. The output also goes into the **server log**, which is located in `domain-dir/logs/server.log`.

To **stop** the GlassFish Server, open a terminal window or command prompt and execute:

```
asadmin stop-domain domain1
```

### List of domains:

```
asadmin list-domains
```


read more:
[quick-start](https://javaee.github.io/glassfish/doc/5.0/quick-start-guide.pdf)