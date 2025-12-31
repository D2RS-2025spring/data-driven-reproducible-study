source("renv/activate.R")

# 设置镜像源
options(
    repos = c(
        CRAN = "https://mirrors.ustc.edu.cn/CRAN"
    ),
    bioc.repos = c(
      BioC = "https://mirrors.ustc.edu.cn/bioc"
    ),
    renv.config.pak.enabled = TRUE
)

# 设置字体
if (!requireNamespace("showtext", quietly = TRUE)) {
  install.packages("showtext")
}
showtext::showtext_auto()

# 设置打印限制
options(max.print = 100)  # 总打印字符数限制为 6 * 6 = 36
options(width = 80)      # 控制每行的宽度，避免过长输出

# 设置 reticulate 的 Python 路径
if (!requireNamespace("reticulate", quietly = TRUE)) {
  install.packages("reticulate")
}
# reticulate::use_condaenv("data-driven-reproducible-study")
