## Issue Fixed #1: Backup repositories were backed up onto multiple locations.
https://github.com/phanandco/security-project-code-copy/commit/46206eec15a655dcd5bf83839047703264f3804a
   A fork branch was created to make sure there is a backup version of the original repository. Modifying and changing the duplicated repository will not affect the contain of the original code. You can also create a pull request to see modifications between the duplicated repository and the original repository. It also retains a version of the repository if one of the repositories get loss or accidentally deleted.
## Issue Fixed #2 
https://github.com/phanandco/security-project-code-copy/commit/b50fce2e8eaae9bc06cd281442d4a2e4ddbb18c6
   A new comment was made within the code to ensure the users that have access to the code that they need the lastest version of the SFML library or else it would not work properly. Installing the lastest update ensures the lastest security and bug fixes implementation to improve user experince and fluidity. The users have Clion or Visual Studio installed on their devices previously to the SFML installation.
   
## SVC 
https://github.com/itsmekhang/security-project-code/pull/3
   This SVC is a pull request of changes and improvements made to the previous version. A pull prequest is just one of the alternative ways to obtain a version control system. It can ensures to highlight the changes made without making changes to the original version.

## Fix 4: using namespace std is removed
By including "using namespace std", you declare all namespace as global. Including using namespace std in the header is limited to the function or class scope.

## Fix 5: Redeclared different shapes as entity classes. Declaring classes allows data encasulation, follows Oject Oriented Programming practices, improve tracibility and maintainability withion the code. Declaring classes controls access to data and functions, that could result in unwanted alterations to sensitive information.

## Fix 6: Implement of smart pointers that would potentially eliminate bound issues. Improve memory allocation and deallocation. Smart pointers eliminate memory leaks.

## Next 4 items to be attempted
- Two-factor authentication when accessing the repository. Difficulty: Easy Priority: Medium
- Implement encryption methods to perform commits. Difficulty: Moderate Priority: Mediium
- User error input logging will be implemented. Difficulty: Moderate Priority: Low
- Local version system control will be implemented. Difficulty: Hard Priority: Low




