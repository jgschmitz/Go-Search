# Go!-Search index creation
Search creation and update examples in Golang for Manish!

<img src="https://raw.githubusercontent.com/docker-library/docs/01c12653951b2fe592c1f93a13b4e289ada0e3a1/golang/logo.png" alt="gocreature" width="100">

The main juxt of it is create one
```
func (siv SearchIndexView) CreateOne(
	ctx context.Context,
	model SearchIndexModel,
	opts ...*options.CreateSearchIndexesOptions,
) (string, error)
```

and update one
```
func (siv SearchIndexView) UpdateOne(
	ctx context.Context,
	name string,
	definition interface{},
	_ ...*options.UpdateSearchIndexOptions,
) error
```
