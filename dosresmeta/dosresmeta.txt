# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Performing dose-response meta-analysis of summarized data Use dosresmeta With (In) R Software
install.packages("dosresmeta")
library("dosresmeta")
dosresmeta = read.csv("https://raw.githubusercontent.com/timbulwidodostp/dosresmeta/main/dosresmeta/dosresmeta.csv",sep = ";")
# Estimation Performing dose-response meta-analysis of summarized data Use dosresmeta With (In) R Software
dosresmeta <- dosresmeta(formula = y ~ dose, id = id, sd = sd, n = n, covariance = "smd", data = dosresmeta)
summary(dosresmeta)
# Performing dose-response meta-analysis of summarized data Use dosresmeta With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished