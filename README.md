I did my best to compile the code but there is always something wrong and I'm so frustrated. I tried literally all versions of Truffle and openzeppelin to make this work but as I said there is always something wrong. I beg you to UPDATE this course!!

here's the last error:
Error parsing /home/ali/Projects/Udacity/2.ethereumSmartContractsTokensandDapps/final-Project2/app/node_modules/@openzeppelin/contracts/token/ERC721/ERC721.sol: ParsedContract.sol:52:72: ParserError: Expected '{' but got reserved keyword 'override'
    function supportsInterface(bytes4 interfaceId) public view virtual override(ERC165, IERC165) returns (bool) {
                                                                       ^------^
Compilation failed. See above.
Truffle v5.0.2 (core: 5.0.2)
Node v16.14.2


1) Your ERC-721 Token Name
    name = Bitmoney

2) Your ERC-721 Token Symbol
    symbol = BM

3) Version of the Truffle and OpenZeppelin used
npm i @openzeppelin/contracts@2.5.1 --force
npm install truffle-hdwallet-provider@1.0.6

Truffle v5.0.2 (core: 5.0.2)
Solidity v0.5.0 (solc-js)
Node v16.14.2

4) Your Token Address on the Rinkeby Network
