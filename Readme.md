# parcel-resolver-exclude-thingos

Tells [parcel](https://github.com/parcel-bundler/parcel) to skip paths includes with `thingos/js/libs`.

## Usage

```
yarn add parcel-resolver-exclude-thingos --dev
```

**.parcelrc**

```json
{
	"extends": "@parcel/config-default",
	"resolvers": ["parcel-resolver-exclude-thingos", "@parcel/resolver-default"]
}
```
