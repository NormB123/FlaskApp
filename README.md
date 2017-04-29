Flask application for use in web server.

This project was accomplished using Python code in the Flask framework.  It uses an Apache2 web server running on a Ubuntu/Linux OS instance on a DigitalOcean virtual server.  It incorporates a sqlite database to house and interact with the application's data, leveraging SQLAlchemy object management for Python.  OAuth security is employed to access Google and Facebook API's to login securely when necessary.

For grader access:
login:  ssh grader@138.197.222.73 -i ~/.ssh/graderKey

graderKey.pub:
ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDrmoIMQKS4LiX1llkVnrNMtmQXhp8PfIEZPQdurTJkvtb4s8AYRXTZV4+tnYvqkl1j+tBEFNtQUHaDwyTUnpVRNoALDzM7z2UiBe22Jv7geDTwPoc6xaXz9I2/yV4H6voc3QwVXF2y6ZDFsyEtBwZC3+opjrrIaNXdejSAFVAuwnyT+nTJUL7ONsOonxK6oDxO7EiG3DOX30JhQMa9Ok68vcH6UT3jjmNKADDyW3CubUdS8jdeOl6yPIyAnc2SNG2h3YXwdPJAgTZcf5zhY24KaqNBvzoz/7MhptIq5m419ZKKG1pPMDgm/PmuIWLpMiZfpA/oYFnDx0xREDv8Zpub sgpilot@NormBissonsAir

password: grader


Required documentation per project Ruberic:

IP address:  138.197.222.73
URL:  http://138.197.222.73/
summary of software installed:  Python, SQLAlchemy, SQLite, Flask, Ubuntu, Apache2 
summary of configurations made:  
	Port assignments: changed ssh port from standard to 2200, disabled unused ports
	Permissions:  Enabled database access for .db files and containing directories (/foundations)
	Users:  Added 'grader' user
list of third-party resources used to completed this project:  
	Udacity Forum
	Udacity Mentor staff 
	Stack Overflow articles
	Apache documentation
	DigitalOcean documentation
	Ubuntu documentation


