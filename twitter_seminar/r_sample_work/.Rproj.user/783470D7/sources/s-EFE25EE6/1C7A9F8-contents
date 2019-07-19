library(readxl)
library(readr)

d <- read_excel("2017UA_sample_data.xlsx", na = "NA")
head(d)

# 出力
write_csv(d, "2017UA_sample_data.csv")

nrow(na.omit(d))

write_csv(na.omit(d), "2017UA_sample_data_delete_na.csv")


