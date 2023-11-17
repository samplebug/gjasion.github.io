<button id="theme-switcher" border="none" color="transparent">Switch Theme</button>

<link rel="stylesheet" href="{{ '/assets/css/light-theme.css' | relative_url }}">
# Greghorz Brezchezyckevisch

## Contact Information
- **Email:** temporaryDown@example.com
- **LinkedIn:** [linkedin.com/in/yourprofile](https://www.linkedin.com/in/yourprofile)
- **GitHub:** [github.com/yourusername](https://github.com/yourusername)
- **Website:** [yourwebsite.com](http://yourwebsite.com)

## Professional Summary
Briefly describe your professional background, skills, and what you are looking for in a new role.

## Skills
<style>
.grid-container {
    display: grid;
    column-gap: 4px;
    grid-template-columns: 240px repeat(7, 12px); 
}

.grid-item-left {
    border: none;
    height: 25px; 
    margin-left: auto; 
    margin-right: 9px;
}

.grid-item {
    height: 12px; 
    margin: 4px 0;
    background-color: #4C9E60;
}

.grid-item-empty {}
	
</style>


<div class="grid-container">
    <div class="grid-item-left">PowerShell</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
            
    <div class="grid-item-left">TSQL</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
       
    <div class="grid-item-left">Git</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
	
    <div class="grid-item-left">C#</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
         
    <div class="grid-item-left">WPF XAML</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
	
    <div class="grid-item-left">Microsoft Power Apps</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
        
    <div class="grid-item-left">Microsoft Power Automate</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    
    <div class="grid-item-left">VBA</div>
    <div class="grid-item"></div>
    <div class="grid-item"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
    <div class="grid-item-empty"></div>
</div>


## Professional Experience
### Job Title, Company Name
#### Month Year - Present
- Detail your responsibilities and achievements.
- Use bullet points for clarity.

### Job Title, Company Name
#### Month Year - Month Year
- Description of your role and contributions.

## Education
### Your Degree, University Name
#### Month Year - Month Year
- Major: Your Major
- Relevant coursework: Course 1, Course 2

## Certifications
- Certification Name, Issuing Organization (Year)
- Another Certification, Issuing Organization (Year)

## Projects
### [Project Title](Link to the project)
Short description of the project.

### [Another Project Title](Link to another project)
Description of another project.

## Languages
- English (Fluent)
 <div style="width: 95%; background-color: #4CAF50; border-radius: 3px; padding: 5px 0;"></div>

- Russian (Can watch and read the news)
 <div style="width: 35%; background-color: #F7996E; border-radius: 3px; padding: 5px 0;"></div>

## Interests
- Interest 1
- Interest 2
 
<script>
    const themeSwitcher = document.getElementById('theme-switcher');
    const currentThemeLink = document.querySelector('link[href*="theme"]');
    const savedTheme = localStorage.getItem('theme');

    if (savedTheme) {
        currentThemeLink.setAttribute('href', savedTheme);
    }

    themeSwitcher.addEventListener('click', function() {
        var isLightTheme = currentThemeLink.getAttribute('href').includes('light-theme');
        var newTheme = isLightTheme ? '{{ "/assets/css/dark-theme.css" | relative_url }}' : '{{ "/assets/css/light-theme.css" | relative_url }}';
        currentThemeLink.setAttribute('href', newTheme);
        localStorage.setItem('theme', newTheme);
    });
</script>
