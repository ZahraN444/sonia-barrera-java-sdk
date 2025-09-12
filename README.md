
# Getting Started with APIMATIC Calculator - zip

## Introduction

Simple calculator API hosted on APIMATIC for demo purposes

## Install the Package

Install the SDK by adding the following dependency in your project's pom.xml file:

```xml
<dependency>
  <groupId>io.github.zahran444</groupId>
  <artifactId>sonia-barrera-sdk</artifactId>
  <version>0.0.1</version>
</dependency>
```

You can also view the package at:
https://central.sonatype.com/artifact/io.github.zahran444/sonia-barrera-sdk/0.0.1

## Initialize the API Client

**_Note:_** Documentation for the client can be found [here.](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/client.md)

The following parameters are configurable for the API Client:

| Parameter | Type | Description |
|  --- | --- | --- |
| httpClientConfig | [`Consumer<HttpClientConfiguration.Builder>`](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-client-configuration-builder.md) | Set up Http Client Configuration instance. |

The API client can be initialized as follows:

```java
import io.apimatic.examples.APIMATICCalculatorZipClient;
import io.apimatic.examples.exceptions.ApiException;
import java.io.IOException;

public class Program {
    public static void main(String[] args) {
        APIMATICCalculatorZipClient client = new APIMATICCalculatorZipClient.Builder()
            .httpClientConfig(configBuilder -> configBuilder
                    .timeout(0))
            .build();

    }
}
```

## List of APIs

* [Simple Calculator](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/controllers/simple-calculator.md)

## SDK Infrastructure

### Configuration

* [Configuration Interface](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/configuration-interface.md)
* [HttpClientConfiguration](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-client-configuration.md)
* [HttpClientConfiguration.Builder](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-client-configuration-builder.md)
* [HttpProxyConfiguration](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-proxy-configuration.md)
* [HttpProxyConfiguration.Builder](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-proxy-configuration-builder.md)

### HTTP

* [Headers](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/headers.md)
* [HttpCallback Interface](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-callback-interface.md)
* [HttpContext](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-context.md)
* [HttpBodyRequest](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-body-request.md)
* [HttpRequest](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-request.md)
* [HttpResponse](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-response.md)
* [HttpStringResponse](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/http-string-response.md)

### Utilities

* [ApiException](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/api-exception.md)
* [ApiHelper](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/api-helper.md)
* [FileWrapper](https://www.github.com/ZahraN444/sonia-barrera-java-sdk/tree/0.0.1/doc/file-wrapper.md)

