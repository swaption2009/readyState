# Wrapping readyState

1) Set network throttling.
2) Wrap an event listener for readystatechange in a Promise.
3) If document.readyState is not 'loading', resolve().
4) Test by chaining wrapperResolved()