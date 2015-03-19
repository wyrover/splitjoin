This is katahiromz's C++ split and join.

---------
string join(const string_container&, char);
string join(const string_container&, const string&);
void split(string_container&, const string&, char);
void split(string_container&, const string&, const string&);
---------

string_container can be:
	std::vector<std::string>,
	std::vector<std::wstring>,
	std::list<std::string>,
	std::list<std::wstring>,
	std::deque<std::string> or
	std::deque<std::wstring>.
