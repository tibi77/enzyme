# `.get(index) => ReactElement`

Returns the node at a given index of the current wrapper.


#### Arguments

1. `index` (`Number`): A zero-based integer indicating which node to retrieve.


#### Returns

`ReactElement`: The retrieved node.


#### Examples

```jsx
const wrapper = shallow(<MyComponent />);
expect(wrapper.find(Foo).get(0).props().foo).to.equal('bar');
```


#### Related Methods

- [`.at(index) => ShallowWrapper`](at.md) - same, but returns the React node in a single-node wrapper.
