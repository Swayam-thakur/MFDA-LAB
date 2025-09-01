Code:
mu <- 400
sigma <- 25
n <- 50
x_bar <- 250
sample_mean <- 15

z <- (x_bar - mu) / (sigma / sqrt(n))

p_value <- 2 * (pnorm(z))

cat(“Z-value:”, z, “\n”)
cat(“P-value:”, p_value, “\n”)

if (p_value < 0.05) {
cat(“Conclusion: Reject the null hypothesis. The claim made by the provider is likely false.\n”)
} else {
cat(“Conclusion: Do not reject the null hypothesis. The claim may be true.\n”)
}
