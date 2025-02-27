# PLATEAU LaTeX Template

This repository contains the LaTeX template for the PLATEAU, which is based on the [ACM LaTeX Template](https://www.acm.org/publications/proceedings-template). 

Use the `plateau` class name without any modifiers:
```
\documentclass{plateau}
```

Specify this year's conference information using the command `\plateauConference[series]{number}{date}{location}`. For example, the 15th annual PLATEAU workshop would be formatted like so:
```
\plateauConference[PLATEAU '25]{15}{February 17--18, 2025}{Boston, MA}
```

Make sure to add the necessary keywords and [ACM CCS Concepts](https://dl.acm.org/ccs) for your work. After you reserve a DOI on KiltHub, specify it using:
```
\plateauDOI{XX.XXXX/XXXXXXX.XXXXXXX}
```

