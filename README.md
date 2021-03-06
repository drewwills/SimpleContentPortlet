# Apereo Simple Content Management Portlet

[![Build Status](https://travis-ci.org/Jasig/SimpleContentPortlet.svg?branch=master)](https://travis-ci.org/Jasig/SimpleContentPortlet)

This Java Portlet is a [Sponsored Portlet][] in the uPortal ecosystem.

## Configuration

See also [documentation in the external wiki][SimpleContentPortlet in Confluence].

### Using Encrypted Property Values

You may optionally provide sensitive configuration items -- such as database passwords -- in encrypted format.  Use the [Jasypt CLI Tools](http://www.jasypt.org/cli.html) to encrypt the sensitive value, then include it in a `.properties` file like this:

```
hibernate.connection.password=ENC(9ffpQXJi/EPih9o+Xshm5g==)
```

Specify the encryption key using the `UP_JASYPT_KEY` environment variable.

[Sponsored Portlet]: https://wiki.jasig.org/display/PLT/Jasig+Sponsored+Portlets
[SimpleContentPortlet in Confluence]: https://wiki.jasig.org/display/PLT/Simple+Content+Management+Portlet
