<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Debugger](./puppeteer.protocol.debugger.md) &gt; [BreakLocation](./puppeteer.protocol.debugger.breaklocation.md)

## Protocol.Debugger.BreakLocation interface

<b>Signature:</b>

```typescript
export interface BreakLocation 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [columnNumber](./puppeteer.protocol.debugger.breaklocation.columnnumber.md) | [integer](./puppeteer.protocol.integer.md) | Column number in the script (0-based). |
|  [lineNumber](./puppeteer.protocol.debugger.breaklocation.linenumber.md) | [integer](./puppeteer.protocol.integer.md) | Line number in the script (0-based). |
|  [scriptId](./puppeteer.protocol.debugger.breaklocation.scriptid.md) | [Runtime.ScriptId](./puppeteer.protocol.runtime.scriptid.md) | Script identifier as reported in the <code>Debugger.scriptParsed</code>. |
|  [type](./puppeteer.protocol.debugger.breaklocation.type.md) | ('debuggerStatement' \| 'call' \| 'return') |  |
