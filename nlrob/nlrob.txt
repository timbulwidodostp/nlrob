# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Robust Fitting of Nonlinear Regression Models Use nlrob (robustbase) With (In) R Software
install.packages("robustbase")
library("robustbase")
nlrob = read.csv("https://raw.githubusercontent.com/timbulwidodostp/nlrob/main/nlrob/nlrob.csv",sep = ";")
# Estimation Robust Fitting of Nonlinear Regression Models Use nlrob (robustbase) With (In) R Software
nlrob <- nlrob(density ~ Asym/(1 + exp((xmid - log(conc))/scal)), data = nlrob, trace = TRUE, start = list(Asym = 3, xmid = 0, scal = 1))
summary(nlrob)
# Robust Fitting of Nonlinear Regression Models Use nlrob (robustbase) With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished