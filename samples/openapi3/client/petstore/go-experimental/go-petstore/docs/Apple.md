# Apple

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Cultivar** | Pointer to **string** |  | [optional] 
**Color** | Pointer to **string** |  | [optional] 

## Methods

### NewApple

`func NewApple() *Apple`

NewApple instantiates a new Apple object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAppleWithDefaults

`func NewAppleWithDefaults() *Apple`

NewAppleWithDefaults instantiates a new Apple object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetCultivar

`func (o *Apple) GetCultivar() string`

GetCultivar returns the Cultivar field if non-nil, zero value otherwise.

### GetCultivarOk

`func (o *Apple) GetCultivarOk() (*string, bool)`

GetCultivarOk returns a tuple with the Cultivar field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetCultivar

`func (o *Apple) SetCultivar(v string)`

SetCultivar sets Cultivar field to given value.

### HasCultivar

`func (o *Apple) HasCultivar() bool`

HasCultivar returns a boolean if a field has been set.

### GetColor

`func (o *Apple) GetColor() string`

GetColor returns the Color field if non-nil, zero value otherwise.

### GetColorOk

`func (o *Apple) GetColorOk() (*string, bool)`

GetColorOk returns a tuple with the Color field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetColor

`func (o *Apple) SetColor(v string)`

SetColor sets Color field to given value.

### HasColor

`func (o *Apple) HasColor() bool`

HasColor returns a boolean if a field has been set.


### AsFruit

`func (s *Apple) AsFruit() Fruit`

Convenience method to wrap this instance of Apple in Fruit

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


