# angular-basics

##  Component Communication
**best practice:** Whenever you don't have a direct parent → child relationship, use a (shared) service to share data and/or send events.

**bad practice:** You could use @Input() in parent component and data binding in the grandparent template to pass a value from grandparent to parent, and use the same mechanism -- @Input() in child and databinding in parent template -- to pass the parent's databound property to the child.
