# Withdrawal-Reward-Logic-The-20-Trigger-
// Withdrawal Process Reward
IF (Withdrawal_Amount >= 1000 && Status == "COMPLETED") {
    CREDIT_SELLER_WALLET(Seller_ID, 20); // ₹20 extra reward for the seller
    NOTIFY_SELLER("Competition Bonus Credited!");
}
