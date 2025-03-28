npm install
Replace the token contract addresses (TokenA and TokenB) with the deployed contract addresses from the backend.
Add Liquidity: Users can add liquidity to the pool by providing equal amounts of TokenA and TokenB.
Remove Liquidity: Users can remove their liquidity and receive an equivalent amount of TokenA and TokenB.
Swap Tokens: Users can swap one token for another within the pool.
addLiquidity(address tokenA, address tokenB, uint256 amountA, uint256 amountB)
removeLiquidity(address tokenA, address tokenB, uint256 liquidityAmount)
swap(address fromToken, address toToken, uint256 amount)
Navigate to the Add Liquidity section of the UI.
Input the token amounts to be added to the liquidity pool (both TokenA and TokenB).
Click the "Add Liquidity" button to deposit the tokens into the pool.
