# ocppostjobs
playbook and role for implementing OCP catalog/template changes as well as configuration changes after cluster deploy

The following playbook and role cover these actions:

Remove a predefined list of unwanted catalog items/image streams
Create the wanted catalog items/image streams
Update new project template
Configure user project quota to zero
Check selinux is enforced


Note: it uses k8s ansible module when possible.  Regarding templates it was not supported, so i used registries and shell commands
