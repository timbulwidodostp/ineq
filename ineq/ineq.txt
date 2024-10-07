# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Measures of inequality Use ineq With (In) R Software
install.packages("ineq")
library("ineq")
ineq = read.csv("https://raw.githubusercontent.com/timbulwidodostp/ineq/main/ineq/ineq.csv",sep = ";")
# Estimation Measures of inequality Use ineq With (In) R Software
ineq_1 <- ineq(ineq$Dependen)
ineq_1
ineq_2 <- ineq(ineq$Dependen, parameter=0.5, type="Atkinson")
ineq_2
# Measures of inequality Use ineq With (In) R Software
# Olah Data Semarang
# WhatsApp : +6285227746673
# IG : @olahdatasemarang_
# Finished