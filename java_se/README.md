Ant template for Java SE project
==================================
## Why do I use Ant?
Ant is a goood tool that don't make you unclear about setting
such as Java compile, JVM setting... Ant is  indepentent any IDE tool.
you can use Ant in your favor IDE editor. For me, I use Emacs and
add Elisp snippets that adds Java stack trace support to 'compilation-mode'.



## Define the architecture of my general use project.


 *project-root					  
 ..src ......... To put your source code		   
 ..build ....... To put classes and jar in the Directory 
 .... classes... To put classes in this floder						   
 .... jar....... Too put jar file in this floder						    
 ..lib ......... Librarys is put in here.		  



## Usage 

### Change variables when you use this file.

**  your-new-prject-name-XXXXXX
 To change name to new project name, Ant script creates a Jar file
 using this name.
**  your-new-main-class-XXXXXX
  To change to a full name that is your main-class name. 

### Command
** To compile file 
``` ant coompile ```

** To run your project given main class name  your-new-main-class-XXXXXX
``` ant run ```

** To clean your project
``` ant clean ```


