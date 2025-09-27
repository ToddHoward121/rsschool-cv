1. Denis Rudenko
2. discord - @toddhoward2388
3. My main goal is to become professional frontend developer. Unfortunately, I don't have work experiense, but I'm ready to learn.
4. Stack:  
    * HTML
    * CSS/SCSS
    * JavaScript
    * TypeScript
    * React  
        * Redux-toolkit
        * Mobx
        * React-hook-form
5. 
```
    export const useDebounce = (value: string, delay: number) => {
        const [debouncedValue, setDebouncedValue] = useState(value);

        useEffect(() => {
            const handler = setTimeout(() => {
                setDebouncedValue(value);
            }, delay);

            return () => {
                clearTimeout(handler);
            };
        }, [value]);

        return debouncedValue;
    }
```

6. I don’t have commercial or team project experience yet, and I haven’t built personal pet projects so far.
However, I’m actively learning and practicing frontend development, and currently working on small project to improve my skills.
7. Self education:
    * JavaScript course - https://js.dmitrylavrik.ru/
    * React fundamental course - https://www.youtube.com/watch?v=GNrdg3PzpJQ
8. English - B1