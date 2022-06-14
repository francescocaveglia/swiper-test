# swiper-test

`npm install`

`npx tsc`

```sh
error TS2430: Interface 'SwiperSlideProps' incorrectly extends interface 'HTMLAttributes<HTMLElement>'.
  Types of property 'children' are incompatible.
    Type 'ReactNode | ((slideData: SlideData) => ReactNode)' is not assignable to type 'ReactNode'.
      Type '(slideData: SlideData) => ReactNode' is not assignable to type 'ReactNode'.

427 interface SwiperSlideProps {
              ~~~~~~~~~~~~~~~~
```
