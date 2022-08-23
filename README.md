
# Boost-HeaderOnly
Boost header only ... just including headers (minimal repo including boost)

> Modules that need build has postfix in names:  **_requireBuild**

### UseCase
Using boost without prebuild(hard build for another systems like some customized OS) , but because it's pure C++ , we can use header only library in it's Compiler and compile with another codes (for example: android studio ndk port)

- [x] tested only on Windows 11 
- [ ] maybe on linux regex should have some changes!
### Custom changes

 1.   Boost.System is now header-only. A stub library is still built for compatibility, but linking to it is no longer necessary. { [Refrence](https://stackoverflow.com/questions/54184576/boost-system-1-69-0-not-header-only#answer-54184692) }

