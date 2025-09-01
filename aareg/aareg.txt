# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Aalen's additive regression model for censored data Use aareg (survival) With (In) R Software
install.packages("survival")
library("survival")
aareg = read.csv("https://raw.githubusercontent.com/timbulwidodostp/aareg/main/aareg/aareg.csv",sep = ";")
# Estimation Competings Risks Regression Model Use comp.risk (timereg) With (In) R Software
aareg <- aareg(Surv(time, status) ~ age + sex + ph.ecog, data = aareg, nmin = 1)
aareg
# Aalen's additive regression model for censored data Use aareg (survival) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished