# BearSDK Landscape Demo
Simple demo showing how landscape orientation can be used

## Notes

Basically to achieve presentation in other orientation than portrait you have to use separated window for `ARViewController`. One way of doing it is shown in this project `AppDelegate`. Project should have portrait and landscape interface orientation listed in `Info.plist`.

Touches should be passed manually to `ARViewController`, if you want to be able to interact with assets in any way.

## Known issues

1. In landscape orientation scanline will move from one side to another (left to right or right to left);
2. When marker is in fixed mode, it will be shown rotated by ±90º.
