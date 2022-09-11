# RS School&-резюме
---
## Alex Wismel
## Contacts
* email: alexwismel@gmail.com
* GitHub: wismel1
---
### Кратко о себе:
I like coming up with new concepts.
---
### Code example
The C++ code. The function to compare two strings in alphabetical order returns a boolean true if the first argument is greater than the second:

bool compare_b_less_a(std::string a, std::string b)
{
	int m = (a.length() < b.length()) ? a.length() : b.length();
	for (int k = 0; k < m; ++k)
		if (a[k] != b[k])
			return (a[k] > b[k]);
	
	return a.length() > b.length();//	
}
---
### Education:
* secondary education
---
### Courses:
* ravesli