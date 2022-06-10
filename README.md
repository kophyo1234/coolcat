
// Address allowed to buy from you
const buyerAddress = "0x4b07329d275ee7e34673defbc973592c7f3758f2"

const listing = await seaport.createSellOrder({
  tokenAddress: "0x2953399124F0cBB46d2CbACD8A89cF0599974963", // Decentraland
  tokenId: "4927369320449798570662940922142418212079342533189746464698124224010817372161", // Token ID
  accountAddress:0x0ae4cAcDe6b5a0d31369b311658e5897ED6b9938 OWNERS_WALLET_ADDRESS,accountAddress:0x0ae4cAcDe6b5a0d31369b311658e5897ED6b9938

  startAmount: 1,
  buyerAddress
})
