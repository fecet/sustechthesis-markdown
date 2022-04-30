# 南方科技大学本科学位论文模板 sustechthesis-markdown

为什么要学LaTeX, 如果你已经会markdown?

# 编译


1. [安装R](https://cran.r-project.org/)

2. 安装`tinytex`,`bookdown`, 进入R命令行:
   ```R
   install.packages("tinytex")
   install.packages("bookdown")
   install.packages("reticulate")
   tinytex::install_tinytex()
   ```

3. ```
    R -e "rmarkdown::render('main.rmd')"
   ```
   首次运行需要较长时间, 因为会自动安装缺失的包



# 上游项目

- [sustechthesis](https://github.com/iydon/sustechthesis)

