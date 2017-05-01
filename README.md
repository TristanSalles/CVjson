# Minimal CV based on JSON standard

JSON-based standard for resumes can be found at https://jsonresume.org.
+ [myCV](https://registry.jsonresume.org/tsalles)

## Command Line Tool
To create your own resume, install resume-cli from npm:

`npm install -g resume-cli`

To install some specific themes:

`npm install -g jsonresume-theme-elegant`

### Exporting to HTML

 Convert your resume to different formats
`resume export resume.html --theme elegant`

### Publishing

You can register an account and publish to jsonresume servers
`resume register`

Then simply type:
`resume publish --theme=elegant`


### Trouble shooting
If when you try to do a  `resume publish` to your account you are not able to enter the email or other details. Try to use the following command first:
`resume login`

