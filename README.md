# 0xanimated
my codes


const element = document.querySelector('.transition-all.duration-300.h-full.w-full.opacity-100.translate-y-0.scale-100');


if (element) {

    const clickInterval = setInterval(() => {
        element.click();
        console.log('Click Done');
    }, 500); 

} else {
    console.log('Click Not Work');
}
