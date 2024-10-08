> [!warning]
> This repository has been deprecated in favor of [@tobiaslabs/eslint-config-javascript](https://github.com/tobiaslabs/eslint-config-javascript), which uses ESLint 9.
> 
> No further updates to this repository will be made or accepted.

# eslint-config-saibotsivad

ESLint and TypeScript configurations that I use across projects I maintain.

## Using

Install the normal way:

```shell
npm install --save-dev eslint @saibotsivad/eslint-config-saibotsivad
```

Create an ESLint config file:

```shell
touch .eslintrc.json
```

Add this config as the base:

```json
{
	"extends": [
		"@saibotsivad/eslint-config-saibotsivad"
	]
}
```

That's it.

That's everything.

(I followed [these directions](https://dev.to/viclafouch/publish-your-own-eslint-prettier-config-for-react-projects-on-npm-g3p) to make this. Thanks [@viclafouch](https://github.com/viclafouch)!)

## License

Published and released under the [Very Open License](http://veryopenlicense.com).
