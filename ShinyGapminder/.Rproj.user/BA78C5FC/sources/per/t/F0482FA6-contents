shinyUI(fluidPage(
  titlePanel("Gapminder Shiny app"),
  
  sidebarLayout(
    sidebarPanel("User inputs will be here",
                 selectInput("select_country", 
                             label = "Country",
                             choices = list("Chad", 
                                            "Iraq", 
                                            "Mali")
                 )
    ),
    mainPanel("My cool graph will go here",
              tableOutput("gapminder_table")
    )
  )
))