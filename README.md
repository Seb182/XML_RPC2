# XML_RPC2


XML_RPC2 is a pear package providing XML_RPC client and server services. XML-RPC is a simple remote procedure call protocol built using HTTP as transport and XML as encoding.
As a client library, XML_RPC2 is capable of creating a proxy class which exposes the methods exported by the server. As a server library, XML_RPC2 is capable of exposing methods from a class or object instance, seamlessly exporting local methods as remotely callable procedures.

- forked from pear/XML_RPC2
- Ready to use with composer in nette project

##### Example composer.json:
```json
{
  "name": "my/project",
  "description": "This is my project...",
  "repositories": [
    {
      "type": "vcs",
      "url": "https://github.com/ludekslevercz/XML_RPC2"
    },
    {
      "type": "git",
      "url": "https://github.com/ludekslevercz/HTTP_Request2"
    }
  ],
  "require": {
    "php": ">= 5.5.1",
    "nette/nette": "~2.3",
    "pear/xml_rpc2": "dev-nette",
    "pear/http_request2": "dev-nette"
  }
}
```

Author: ludek@slever.cz
