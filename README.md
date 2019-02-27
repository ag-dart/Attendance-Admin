[![DevOps By Rultor.com](http://www.rultor.com/b/yegor256/rultor)](http://www.rultor.com/p/yegor256/rultor)
[![CircleCI](https://circleci.com/gh/ammaratef45/Attendance-Admin/tree/master.svg?style=svg)](https://circleci.com/gh/ammaratef45/Attendance-Admin/tree/master)
# Attendance-Admin
Hello! 
We are pleased to share the QR-Attendance source code of the Admin version. The Admin version is designed for users whose job is meant to manage the attendance of a group of persons to a lecture meeting or any similar professional and non-professional gatherings. The App provides an environment that manges its users from creating profiles for their lectures or meetings each one characterized by a QR code that can be shared with the students or the meeting attendees to register their attendance via the user version of the App installed on their mobile phones.

We believe that sharing this effort with you will eventually end up with a more solid and sustainable code that will satisfy the users requirements. We're so excited to hear your comments and see your priceless contributions. 

Thanks in advance!

## Download
You can get the Android beta version [here](https://play.google.com/store/apps/details?id=com.ammar.attendanceadmin)

iOS beta version coming soon

No stable version submitted yet!

## Donation
We pay money to keep this app available and to keep developing it.
Only sources of money is small ads that will be added later and it will not a bothering or heavy ads so it's not expected to save a be a lot of money.

If you are willing to [donate](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=U6NJRDMCD3ET2&source=url), That will help the project.

# Ho to contribute

## installation
- Install Flutter
- Switch to dev channel flutter channel dev
- Upgrade flutter flutter upgrade
- Run tests flutter test
- Run app flutter run

You can use docker image ammaratef45/flutter:latest

## Install RVM (for pdd)
- `curl -sSL https://get.rvm.io | bash -s stable --ruby`
- `gem install pdd`

## contribution
- Make a fork.
- Pick an issue you want to solve, or implement a feature.
- Run the following commands before make a PR and make sure no one fails.
```
flutter packages get
flutter test
flutter -v build apk
pdd -f /dev/null -v
```
- Submit a PR
