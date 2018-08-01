# personal_site
my own personal site
install.packages("rmarkdown", type = "source")
touch _site.yml #"YML" file that tells your website how to assemble itself
touch index.Rmd #Create the main rmd file
touch about.Rmd #Create an about file

name: "jimmyxu-website"
output_dir: "."
navbar:
  title: "Nicks Website"
  left:
    - text: "Home"
      href: index.html
    - text: "About Me"
      href: about.html
