# AdminUpdateIdentityBody

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**MetadataAdmin** | Pointer to **interface{}** | Store metadata about the user which is only accessible through admin APIs such as &#x60;GET /admin/identities/&lt;id&gt;&#x60;. | [optional] 
**MetadataPublic** | Pointer to **interface{}** | Store metadata about the identity which the identity itself can see when calling for example the session endpoint. Do not store sensitive information (e.g. credit score) about the identity in this field. | [optional] 
**SchemaId** | **string** | SchemaID is the ID of the JSON Schema to be used for validating the identity&#39;s traits. If set will update the Identity&#39;s SchemaID. | 
**State** | [**IdentityState**](IdentityState.md) |  | 
**Traits** | **map[string]interface{}** | Traits represent an identity&#39;s traits. The identity is able to create, modify, and delete traits in a self-service manner. The input will always be validated against the JSON Schema defined in &#x60;schema_id&#x60;. | 

## Methods

### NewAdminUpdateIdentityBody

`func NewAdminUpdateIdentityBody(schemaId string, state IdentityState, traits map[string]interface{}, ) *AdminUpdateIdentityBody`

NewAdminUpdateIdentityBody instantiates a new AdminUpdateIdentityBody object
This constructor will assign default values to properties that have it defined,
and makes sure properties required by API are set, but the set of arguments
will change when the set of required properties is changed

### NewAdminUpdateIdentityBodyWithDefaults

`func NewAdminUpdateIdentityBodyWithDefaults() *AdminUpdateIdentityBody`

NewAdminUpdateIdentityBodyWithDefaults instantiates a new AdminUpdateIdentityBody object
This constructor will only assign default values to properties that have it defined,
but it doesn't guarantee that properties required by API are set

### GetMetadataAdmin

`func (o *AdminUpdateIdentityBody) GetMetadataAdmin() interface{}`

GetMetadataAdmin returns the MetadataAdmin field if non-nil, zero value otherwise.

### GetMetadataAdminOk

`func (o *AdminUpdateIdentityBody) GetMetadataAdminOk() (*interface{}, bool)`

GetMetadataAdminOk returns a tuple with the MetadataAdmin field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataAdmin

`func (o *AdminUpdateIdentityBody) SetMetadataAdmin(v interface{})`

SetMetadataAdmin sets MetadataAdmin field to given value.

### HasMetadataAdmin

`func (o *AdminUpdateIdentityBody) HasMetadataAdmin() bool`

HasMetadataAdmin returns a boolean if a field has been set.

### SetMetadataAdminNil

`func (o *AdminUpdateIdentityBody) SetMetadataAdminNil(b bool)`

 SetMetadataAdminNil sets the value for MetadataAdmin to be an explicit nil

### UnsetMetadataAdmin
`func (o *AdminUpdateIdentityBody) UnsetMetadataAdmin()`

UnsetMetadataAdmin ensures that no value is present for MetadataAdmin, not even an explicit nil
### GetMetadataPublic

`func (o *AdminUpdateIdentityBody) GetMetadataPublic() interface{}`

GetMetadataPublic returns the MetadataPublic field if non-nil, zero value otherwise.

### GetMetadataPublicOk

`func (o *AdminUpdateIdentityBody) GetMetadataPublicOk() (*interface{}, bool)`

GetMetadataPublicOk returns a tuple with the MetadataPublic field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetMetadataPublic

`func (o *AdminUpdateIdentityBody) SetMetadataPublic(v interface{})`

SetMetadataPublic sets MetadataPublic field to given value.

### HasMetadataPublic

`func (o *AdminUpdateIdentityBody) HasMetadataPublic() bool`

HasMetadataPublic returns a boolean if a field has been set.

### SetMetadataPublicNil

`func (o *AdminUpdateIdentityBody) SetMetadataPublicNil(b bool)`

 SetMetadataPublicNil sets the value for MetadataPublic to be an explicit nil

### UnsetMetadataPublic
`func (o *AdminUpdateIdentityBody) UnsetMetadataPublic()`

UnsetMetadataPublic ensures that no value is present for MetadataPublic, not even an explicit nil
### GetSchemaId

`func (o *AdminUpdateIdentityBody) GetSchemaId() string`

GetSchemaId returns the SchemaId field if non-nil, zero value otherwise.

### GetSchemaIdOk

`func (o *AdminUpdateIdentityBody) GetSchemaIdOk() (*string, bool)`

GetSchemaIdOk returns a tuple with the SchemaId field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetSchemaId

`func (o *AdminUpdateIdentityBody) SetSchemaId(v string)`

SetSchemaId sets SchemaId field to given value.


### GetState

`func (o *AdminUpdateIdentityBody) GetState() IdentityState`

GetState returns the State field if non-nil, zero value otherwise.

### GetStateOk

`func (o *AdminUpdateIdentityBody) GetStateOk() (*IdentityState, bool)`

GetStateOk returns a tuple with the State field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetState

`func (o *AdminUpdateIdentityBody) SetState(v IdentityState)`

SetState sets State field to given value.


### GetTraits

`func (o *AdminUpdateIdentityBody) GetTraits() map[string]interface{}`

GetTraits returns the Traits field if non-nil, zero value otherwise.

### GetTraitsOk

`func (o *AdminUpdateIdentityBody) GetTraitsOk() (*map[string]interface{}, bool)`

GetTraitsOk returns a tuple with the Traits field if it's non-nil, zero value otherwise
and a boolean to check if the value has been set.

### SetTraits

`func (o *AdminUpdateIdentityBody) SetTraits(v map[string]interface{})`

SetTraits sets Traits field to given value.



[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


