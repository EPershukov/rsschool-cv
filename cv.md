# Evgeny Pershukov

_Minsk, Belarus  
+375 29 573-6685 
Email: [epershukov@gmail.com](mailto:epershukov@gmail.com)  
LinkedIn: [linkedin.com/in/evgeny-pershukov](https://www.linkedin.com/in/evgeny-pershukov/)  
GitHub: [github.com/EPershukov](https://github.com/EPershukov)  
CodeWars: [codewars.com/users/MrLansky](https://www.codewars.com/users/MrLansky)_

## Summary

QA / QA Automation in JS, now try as Web developer

## Skills // TODO

&#9724;&#9724;&#9724;&#9724;&#9723; JavaScript  
&#9724;&#9724;&#9724;&#9724;&#9723; Node.js  
&#9724;&#9724;&#9724;&#9723;&#9723; Mocha/Jest  
&#9724;&#9724;&#9724;&#9723;&#9723; SQL  
&#9724;&#9724;&#9724;&#9723;&#9723; GIT  
&#9724;&#9724;&#9724;&#9724;&#9723; Vusial Studio Code  
&#9724;&#9724;&#9724;&#9723;&#9723; TypeScript  
&#9724;&#9724;&#9724;&#9723;&#9723; Platwright / webdriverIO

## Code samples

**TypeScript:**

```typescript
async function checkElements(selectors: {[selectorName:string]:string}): Promise<string[]> {
    const fails: string[] = [];
    for(let [selectorName, selector] of Object.entries(selectors)) {
      await waits
        .waitForAttached(selector)
        .then()
        .catch(() => fails.push(`${selectorName} = ${selector}`));
    }
    return fails;
  }
```

## Experience

**SpurIT e-commerce solution**
_since 2018 as QA/QA Automation engineer_

## Education

**Belarusian State University of Radiophysics and Computer Science (2011-2016)**
_Physic-engineer_

#### Courses:

- QA Academy (Basic course 2017)

## English level is Pre-intermediate