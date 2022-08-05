# PowerPoint-Touchportal-Private



# PowerPoint Plugin - For TouchPortal
  - [Description](#description) 
  - [Features](#features)
    - [Actions](#actions)
    - [States](#states)
  - [Bugs and Support](#bugs-and-suggestion)

  
# Description
## The Plugin Sample Page
![image](https://user-images.githubusercontent.com/76603653/183006476-25ebc4a0-be66-47ab-a6c6-4f78007220f2.png)


# Features
Control your PowerPoint presentation with TouchPortal

## Actions
|Action Name|Description|Format|
|---|---|---|
| Open Presentation | Load the presentation | 1. Type: text &nbsp;<empty>|
|Start Presentation | Start the Presentation |1.  Type: text &nbsp;<empty>|
|Previous Slide |Go Back to Previous Slide |1.  Type: text &nbsp;<empty>|
|Next Slide|Proceed to Next Slide |1.  Type: text &nbsp;<empty>|
|First Slide |Proceed to First Slide |1.  Type: text &nbsp;<empty>|
|Last Slide |Proceed to Last Slide |1.  Type: text &nbsp;<empty>|
|Go to Slide |Proceed to Slide [X] |1.  Type: text &nbsp;<empty>|
|Exit Slides |Exit Current Slideshow|1.  Type: text &nbsp;<empty>|
|Minimize / Maximize Powerpoint |Change Powerpoint Display to [X]|1.  Type: choice **** Possible choices: ['Minimize', 'Maximize', 'Visible']|



## States
<details open id='gitago.powerpoint.mainstates'><summary><b>Category:</b> PowerPoint <small><ins>(Click to expand)</ins></small></summary>


| Id | Description | DefaultValue | 
| --- | --- | --- |
| .state.last_slide_viewed | Last Slide Viewed # | Last Slide Viewed |  |   
| .state.current_show_position | Current Slide # | Current Show Position |  |   
| .state.click_count_index | Current Clicks on Slide & Current Click Index | Slide Click Count / Index |  |   
| .state.elapsed_time_presentation | Total Time Presentation Open | Elapsed Time Presentation |  |   
| .state.elapsed_time_slide | Total Time on Slide | Elapsed Time Slide |  |   
</details>

<br>

# Bugs and Suggestion
Open an issue on github or join offical [TouchPortal Discord](https://discord.gg/MgxQb8r) for support.



