# useDebounce-custom-hook
custom hook for ReactJS to debounce function


### Usage

    const debouncedFn = useDebounce(value => {
        console.log('value :>> ', value);
    }, 500);
    
    debouncedFn(value);
