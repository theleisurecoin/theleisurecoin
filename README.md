static inline unsigned short GetDefaultPort(const bool testnet = fTestNet)
{
    return testnet ? 6613 : 6875;
}

assert(block.hashMerkleRoot == uint256("0xa57103188b2f766467ea7b88126b73f4831f56d8d56306bcba93a45f143c6c2e"));

hashGenesisBlockOfficial("0x0bfc59961a49a2f12dbb764bed1b40e3c84a2ab936ac1e2984cf10a1c5fa074d");

static inline unsigned short GetDefaultRPCPort()
{
    return GetBoolArg("-testnet", false) ? 5162 : 5214;
}
