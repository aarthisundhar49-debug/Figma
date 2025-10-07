# Ex09 Event Registration Web Application
## Date:07.10.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
import React from "react";
import rectangle3 from "./rectangle-3.png";
import screenshot202510061322081 from "./screenshot-2025-10-06-132208-1.png";

export const Frame = () => {
  return (
    <div className="bg-[#d2bcf0] w-full min-w-[265px] min-h-[533px] relative">
      <img
        className="absolute top-0 left-0 w-[265px] h-[533px] object-cover"
        alt="Rectangle"
        src={rectangle3}
      />

      <div className="absolute top-60 left-[69px] w-[117px] h-[43px] flex bg-[#af2424]">
        <div className="mt-3 w-[66px] h-[19px] ml-[37px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
          LOGIN
        </div>
      </div>

      <div className="absolute top-[171px] left-[69px] w-[125px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        SPORTS DAY EVENTS
      </div>

      <img
        className="absolute top-[55px] left-[11px] w-[248px] h-[76px] aspect-[3.28] object-cover"
        alt="Screenshot"
        src={screenshot202510061322081}
      />

      <div className="absolute top-[307px] left-[52px] w-[134px] h-[57px] bg-[#d9d9d9]" />

      <div className="absolute top-[328px] left-[98px] w-[59px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        REGISTER
      </div>
    </div>
  );
};
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}
import React from "react";
import screenshot202510071523131 from "./screenshot-2025-10-07-152313-1.png";

export const Frame = () => {
  return (
    <div className="bg-[#50f6d7] w-full min-w-[302px] min-h-[529px] relative">
      <img
        className="absolute top-0 left-0 w-[302px] h-[529px] aspect-[0.63] object-cover"
        alt="Screenshot"
        src={screenshot202510071523131}
      />

      <div className="absolute top-[122px] left-[65px] w-[103px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
        VOLLEY BALL
      </div>

      <div className="absolute top-8 left-[122px] w-[78px] [font-family:'Inter-Regular',Helvetica] font-normal text-black text-xs tracking-[0] leading-[normal]">
        &nbsp;&nbsp;&nbsp;&nbsp;EVENTS
      </div>

      <div className="absolute top-[93px] left-[59px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
        &nbsp;&nbsp;CRICKET
      </div>

      <div className="absolute top-40 left-[71px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
        BADMINTON
      </div>

      <div className="absolute top-52 left-[75px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
        500 MTS
      </div>

      <div className="absolute top-[250px] left-[88px] [font-family:'Inter-Regular',Helvetica] font-normal text-white text-xs tracking-[0] leading-[normal]">
        RELAY
      </div>
    </div>
  );
};
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}
import React from "react";
import screenshot202510071542131 from "./screenshot-2025-10-07-154213-1.png";

export const Image = () => {
  return (
    <div className="w-[356px] h-[526px]">
      <img
        className="fixed top-[15px] left-[18px] w-[286px] h-[511px] aspect-[0.68] object-cover"
        alt="Screenshot"
        src={screenshot202510071542131}
      />
    </div>
  );
};
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./src/**/*.{html,js,ts,jsx,tsx}"],
  theme: {
    extend: {},
  },
  plugins: [],
};
@tailwind components;
@tailwind utilities;

@layer components {
  .all-\[unset\] {
    all: unset;
  }
}

:root {
  --animate-spin: spin 1s linear infinite;
}

.animate-fade-in {
  animation: fade-in 1s var(--animation-delay, 0s) ease forwards;
}

.animate-fade-up {
  animation: fade-up 1s var(--animation-delay, 0s) ease forwards;
}

.animate-marquee {
  animation: marquee var(--duration) infinite linear;
}

.animate-marquee-vertical {
  animation: marquee-vertical var(--duration) linear infinite;
}

.animate-shimmer {
  animation: shimmer 8s infinite;
}

.animate-spin {
  animation: var(--animate-spin);
}

@keyframes spin {
  to {
    transform: rotate(1turn);
  }
}

@keyframes image-glow {
  0% {
    opacity: 0;
    animation-timing-function: cubic-bezier(0.74, 0.25, 0.76, 1);
  }

  10% {
    opacity: 0.7;
    animation-timing-function: cubic-bezier(0.12, 0.01, 0.08, 0.99);
  }

  to {
    opacity: 0.4;
  }
}

@keyframes fade-in {
  0% {
    opacity: 0;
    transform: translateY(-10px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes fade-up {
  0% {
    opacity: 0;
    transform: translateY(20px);
  }

  to {
    opacity: 1;
    transform: none;
  }
}

@keyframes shimmer {
  0%,
  90%,
  to {
    background-position: calc(-100% - var(--shimmer-width)) 0;
  }

  30%,
  60% {
    background-position: calc(100% + var(--shimmer-width)) 0;
  }
}

@keyframes marquee {
  0% {
    transform: translate(0);
  }

  to {
    transform: translateX(calc(-100% - var(--gap)));
  }
}

@keyframes marquee-vertical {
  0% {
    transform: translateY(0);
  }

  to {
    transform: translateY(calc(-100% - var(--gap)));
  }
}
```

## OUTPUT:
![alt text](<Screenshot 2025-10-07 160550.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
