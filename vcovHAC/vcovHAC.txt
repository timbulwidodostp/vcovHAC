# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Heteroscedasticity and Autocorrelation Consistent (HAC) Covariance Matrix Estimation Use vcovHAC And vcov (sandwich) With (In) R Software
install.packages("sandwich")
library("sandwich")
vcovHAC = read.csv("https://raw.githubusercontent.com/timbulwidodostp/vcovHAC/main/vcovHAC/vcovHAC.csv",sep = ";")
# Estimation Heteroscedasticity and Autocorrelation Consistent (HAC) Covariance Matrix Estimation Use vcovHAC And vcov (sandwich) With (In) R Software
vcovHAC <- lm(Dependen ~ Independen_1 + Independen_2 + Independen_3, data = vcovHAC)
vcovHAC(vcovHAC)
vcov(vcovHAC)
# Heteroscedasticity and Autocorrelation Consistent (HAC) Covariance Matrix Estimation Use vcovHAC And vcov (sandwich) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished