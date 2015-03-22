This is katahiromz's C++ split and join.

---------
string joinbychar(const string_container&, char);
string join(const string_container&, const string&);
void splitbychar(string_container&, const string&, char);
void split(string_container&, const string&, const string&);
void tokenize(string_container&, const string&, const string&);
---------

string_container can be:
	std::vector<std::string>,
	std::vector<std::wstring>,
	std::list<std::string>,
	std::list<std::wstring>,
	std::deque<std::string> or
	std::deque<std::wstring>.

You can also specify std::set<std::string> or 
std::unordered_set<std::string> to joinbychar and join.
