# Automated PowerPoint Generator for ICT Diagnostic Tools

## 📌 Concept Overview
his project automatically generates a PowerPoint presentation using Python for a topic titled “Diagnostic Tools of ICT.” It uses the python-pptx library to:

Create slides

Add titles and bullet points

Add custom background images

Format text size and color

This is useful for students, teachers, or presenters who want to build presentations programmatically without manually designing each slide.

## 📚 What Are ICT Diagnostic Tools?
- ICT (Information and Communication Technology) diagnostic tools are software and      hardware resources used to detect, troubleshoot, and maintain computer systems and     networks.
- They help ensure system health, security, and efficiency.

This presentation explains types of diagnostic tools:

- Hardware tools like POST, multimeters
- Software tools like Task Manager, Wireshark
- Their uses, advantages, and emerging trends

## 🧠 Technical Terms Used
| Term/Library                          | Meaning                                                             |
| ------------------------------------- | ------------------------------------------------------------------- |
| `python-pptx`                         | A Python library for creating and editing PowerPoint (.pptx) files. |
| `Presentation()`                      | Creates a new PowerPoint presentation object.                       |
| `prs.slide_width`, `prs.slide_height` | Set the size of the slides (in inches).                             |
| `add_slide()`                         | Adds a new slide to the presentation.                               |
| `add_picture()`                       | Inserts an image (used as background).                              |
| `add_textbox()`                       | Adds a text box (used for title and content).                       |
| `text_frame`, `add_paragraph()`       | Handles multi-line and formatted text.                              |
| `Pt()`                                | Sets font size in points.                                           |
| `RGBColor()`                          | Sets font color using RGB values.                                   |


## 🧾 How the Code Works (Simplified & Concise)
1. Imports Libraries
Loads required libraries to create PowerPoint presentations, set font size, and manage colors.

2. Creates a Presentation
Initializes a new PowerPoint and sets the slide size to widescreen (13.33 x 7.5 inches).

3. Defines Slide Content
Uses a list of slides, each with a title, bullet point content, and a background image.

4. Adds Slides Automatically
For each slide:

- Adds a blank layout
- Inserts a background image
- Adds a title in large, bold, white font
- Adds bullet points (split by line breaks) in medium-sized white font

5. Saves the Final Presentation
After adding all slides, it saves the result as Diagnostic_Tools_of_ICT_Presentation.pptx.

                                 # prepared by; Nikodimos Elias G/Egziabher
                                 # Junior Software Developer
