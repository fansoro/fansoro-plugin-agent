# Morfy Agent Plugin
The user agent plugin provides a simple way to detect the kind of device that made the request.   

## Installation
See [this instruction](http://morfy.org/documentation/plugins/plugins-installation)

## Usage in templates

Detect mobile device

```smarty
{if Agent::isMobile()}
    // Do something...
{/if}
```

Detect robot or crawler

```smarty
{if Agent::isRobot()}
    // Do something...
{/if}
```

Detect specific device

```smarty
{if Agent::is('iphone')}
    // Do something...
{/if}
```

## Options

| name  | value | description |
|---|---|---|
| enabled | true | or `false` to disable the plugin |

## License
See [LICENSE](https://github.com/morfy-cms/morfy-plugin-agent/blob/master/LICENSE)
