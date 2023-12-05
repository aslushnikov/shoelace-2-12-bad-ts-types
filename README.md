# Repro steps

```sh
git clone https://github.com/aslushnikov/shoelace-2-12-bad-ts-types
cd shoelace-2-12-bad-ts-types
npm i
npx tsc
```

Expected: no errors
Actual:

```
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(1,43): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(2,41): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(3,39): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(4,39): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(5,34): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(6,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(7,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(8,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(9,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(10,38): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(11,34): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(12,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(13,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(14,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(15,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(16,34): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(17,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(18,42): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(19,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(20,37): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(21,40): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(22,38): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(23,34): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(24,38): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(25,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(26,40): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(27,42): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(28,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(29,36): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(30,45): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(31,34): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(32,41): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(33,35): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(34,37): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
node_modules/@shoelace-style/shoelace/dist/events/events.d.ts(35,37): error TS2834: Relative import paths need explicit file extensions in ECMAScript imports when '--moduleResolution' is 'node16' or 'nodenext'. Consider adding an extension to the import path.
```
