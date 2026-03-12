# markdown-language-convert-to-pain-text


```jsx 
npm install react-markdown remark-gfm



import Markdown from 'https://esm.sh/react-markdown@10'
import remarkGfm from 'remark-gfm';



<Markdown remarkPlugins={[remarkGfm]}>
{msg.message}
</Markdown>


<div className="text-sm max-w-xs xl:max-w-none break-words whitespace-normal [&_h3]:mt-3 [&_h3]:mb-2 [&_h3]:font-semibold [&_p]:mb-2 [&_p:last-child]:mb-0 [&_ol]:list-decimal [&_ol]:pl-5 [&_ul]:list-disc [&_ul]:pl-5 [&_li]:mb-1 [&_table]:w-full [&_table]:border-collapse [&_th]:border [&_th]:border-gray-300 [&_th]:px-2 [&_th]:py-1 [&_th]:text-left [&_td]:border [&_td]:border-gray-300 [&_td]:px-2 [&_td]:py-1 [&_table]:text-xs sm:[&_table]:text-sm">
                            <ReactMarkdown remarkPlugins={[remarkGfm]}>{text}</ReactMarkdown>
                            {/* this div class css is important, plays crusial roles */}
                        </div>



```
