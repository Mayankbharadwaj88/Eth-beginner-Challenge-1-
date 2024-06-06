# Types Contract

The `types` contract is a basic Solidity smart contract that demonstrates how to use different data types in Ethereum smart contracts. The contract includes functions to set and get values of the following types: `uint`, `int`, `bool`, `address`, and `string`.



### State Variables used 

- `uint public a;` - An unsigned integer
- `int public b;` - A signed integer
- `bool public c;` - A boolean
- `address public d;` - An Ethereum address
- `string public e;` - A string

### Functions

#### Unsigned Integer (uint)

- `function setuint(uint _a) public returns (uint)` - Sets the value of `a` to `_a` and returns the new value.
- `function getuint() public view returns (uint)` - Returns the current value of `a`.

#### Signed Integer (int)

- `function setint(int _b) public returns (int)` - Sets the value of `b` to `_b` and returns the new value.
- `function getint() public view returns (int)` - Returns the current value of `b`.

#### Boolean (bool)

- `function setbool(bool _c) public returns (bool)` - Sets the value of `c` to `_c` and returns the new value.
- `function getbool() public view returns (bool)` - Returns the current value of `c`.

#### Address (address)

- `function setaddress(address _d) public returns (address)` - Sets the value of `d` to `_d` and returns the new value.
- `function getaddress() public view returns (address)` - Returns the current value of `d`.

#### String (string)

- `function setstring(string memory _e) public returns (string memory)` - Sets the value of `e` to `_e` and returns the new value.
- `function getstring() public view returns (string memory)` - Returns the current value of `e`.

