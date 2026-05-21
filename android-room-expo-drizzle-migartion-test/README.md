# Android Room To Expo Drizzle Migration Test Suite

This test ensure that the user when updating to v3.0.0+ from prior v2.x.x not lost thier data.

## Why this test needed?

As you may have know that we moving from native android (kotlin) to React Native from v2 to v3. So we as developer need ensure that data flows correctly...

Utill now your data is handle by what called "Room" (android standard framework for local databases).
Now we will use what called "Drizzle" a popular database tool that standard for expo databases.
So we need test that data flow correctly...

## Analytics and Constraints

From what I have known, thier are around at MAX 50-60 app users in total. As of May 21, 2026...

Based on github downloads api, telegram and discord community... I can say, there are about-around 75 app downloads...
Based on that i can say that thier will be around 25 active users at max. And, 5/6 will be genuine users as of my assumptions..

So, we are here serveing very small group of genunine users <10...

## Assume

Either ways, we can assume that <10 users are on latest versions. and thus we will assume that if we are migrate from v2.1.1 to v3.0.0 without data lost we can surely do the same with any prior versions (let say with v1.2.0 also).

## Steps To Test.

0. If have ever test the passcodes app before. then ensure that you have no other then production version of passcodes install on your device.

1. Download the new test suite app given in [gh-release (comming-soon)]().

2. Install app as normal and open it.

3. Now download the `extra-test-passwords.csv` from [gh-release (comming-soon)]().

4. Now you can use import features of app to auto-add extra test passwords.

5. If wish, you also add your custom one or two password it real help use test app better due to your custom input to test... (HIGH ENCOURAGE IT)

6. Close app complete.

7. Now download the new updated apk from [gh-release (comming-soon)]() and install it.

8. Run the app & just act / pretend like user, if you are developer be little impatient (if you want to)...

9. After app done being hang (yeah it may feel like it hanged)... Check wether your passwords are still thier.

10. Report a one word success or failure.. and if you want along with long story of your wait on discord/telegram...
