
# How to think like a data scientist in industry

At Insight, we help high achieving scientists transition from academia to industry. In this short article, I will highlight how to think more like a data scientist in industry and how previous fellows at Insight have demonstrated this ability to get jobs at leading companies.


## Focus on product and the business impact

Pretend for a moment you are a data scientist at a company that is considering whether or not to add a feature to a product. To help make your decision, you might use the following questions to drive your analysis.

1) How are users currently interacting with that product? 
2) What does that product currently lack that causes a pain point for users?
3) What would a quick solution to these users problems look like?
4) What is the potential benefit for the company?

It's important to understand how your work helps move a product forward, or how it enables the business of a company to grow. Focusing on the real problems your users have anchors your project and helps motivate the subsequent choices you make.

- **Example**: "Finding art for your home can be a difficult and time consuming process. Purchasing art online is especially challenging because online retailers use keywords to describe visual imagery. Potential art enthusiasts are challenged with accurately describing art in search bars. The customer experience, and sales, for companies like Etsy or Artsy would be improved if users could provide an example of paintings that they liked and were shown other paintings that matched the visual subtleties of the examples provided.

![](./media/paintbynumbers.svg)

![](https://lh3.googleusercontent.com/jNcy3dKKlNbALPDXqrmTZgjF4hecNw4zmJzYM5RGQ1hll_2J1UMlqLBSnR4E06kbksWYWdeEUY7_NAEDRLfQywxCUv2gElJ5Od76Q0my2eewGSpNDpMX2aOKkDWbmnFXVo5MFTukajr5YU_d803zpMVxURjANZREDqNSR5kw4khS4ChYz2sTAtEnxD26-66n407e1XnGmVkLy-etuexq0t3KRT6bfF9bK_VL-CtCgu9oIGWosVDiSXGmo8ZLyCoXCLIsslwkc4rt2KxO6J0y9gXFSpwnuWoyTT5UozRvgpXH4OayQrmzU3SV3c2msJGkFMxzaVKgAwE5XWyMBuZSQ_J6yfWZzCYylmdtc0uGNhyCJWPSkPyAaSInIoTHt53x7BZUnQHCYuXXBMPBwXZjE72zhmjdnoAQfoFABGtwEUJ8OOcaDjBZ_QQA3ycdltbliMiB6BL0SsqcVh3depmr-4b7gH1hk4Z2OczQB8to1Ucppb6qsT3bNIxbADV5ghTS-qQKOj8GfGakjjfoDp4i95pWsAjCMFmgZgp28CAcniGyr1e8VfuhoYCahEhfaeCpDiWVG18awJl4Qg3lh2-FTbppcbrY0rRc3IoqiZl8oHRIrWq3BbqTlxoWexyZs-r2L56wopmskMbva6MVuCkAD8A1D7dEDtXgRRJQ2IpDcZ85TYrHTkxuVZI=w1280-h720-no)

![](https://lh3.googleusercontent.com/-553Z2KzVCc3bTtyI48BrXUdug0KQhlWI9xTGP1mNK9WUrave1W45DuGrM22GV-8ZK6cXLT7pw_xG15uV_2gXJGXPycRb8IJ3nE1RieVf11_0CPzeBneDujwjGb7YeqfYzGnhQ47zF-VJZN8cvf-Sglxdbc6KP_ObsruM1sSBw9ZiB_W5gQpZWDHOKCxP38J0bL8oTLYEIyODb_uHa6dxxvvdGefNRJ4yDrieKHXl7CvOyOS2z4Vcuyyu8vZrIbG3FtpzYvDP34duTraEHKodLD43LPIcbD2LjxuyK1mVsDRiKUkRekAjthRSWZRy40SBz-2cfawDPteSoxLjo-3LNjRMvH9cXVyNDufKaDgajUVBvnSy4ASwD0brivp-zSNjCPTyy7iBkvJgJg6X0terQK1smGHZJ-Bz-yNYUu2agzZO_Qid0Rj407h8od9t2xUZTHVJcc84g0TgZBUfSdQvm1xAxosSeLAb4sT_l318Lf2Kt05yPOwFNrzh1_zYOsxGXwszVLRkIy-BG6E3U_gcgvRtFFqcIIa07Cy6kzrJE8shTlsyfMWwAgm8LEU5FW4az82oL7QTobudb8Q7kclJHvByFrlsB9lINUaJp9JDmiWCQ40JiwMbLJtHxj0sL2MVmQmsIv-J6Tf4pH4SJoY8uh5xLqWUTEichrYwUoS7ywqLjQsU7PUH58=w1280-h720-no)

Paint by Numbers by [Justin Morse](https://www.linkedin.com/in/jcmorse/)

- **Commentary**: In the e-commerce world, consumers are often paralyzed by an overabundance of choice. A simple search for art on Etsy can yield hundreds of thousands of results. This project helped simplify the purchasing process by allowing users to drop in or take a picture of their favorite pieces of art and by using computer vision to identify latent image features that matched art on the Etsy and Artsy marketplaces. Users were then provided recommendations of similar pieces of art at multiple price points, so that they could select the right piece for their budget.

## Know what the right data is to solve your problem

Once you have a problem defined, it's important to consider what data you need. These days, companies have almost *too much* data, forcing data scientists to consider which sources of data are most relevant for their problem. One way to do this is to continue to refer back to how your user, company, or community of users interact with the product or business. How is that data captured? How much of that data is available and what can you do with it?

Sometimes the data you need doesn't exist. In cases like this, you may have to get creative to find a solution. You might have to combine different datasets to serve as a proxy for what you want to measure.

- **Example**: "NYC Parks is tasked with managing over 600,000 street trees, but has the resources to inspect and maintain less than 50,000 trees per year. Currently, NYC relies on highly-biased citizen-submitted tree service requests to prioritize trees for maintenance, which results in over 10,000 tree branch falls per year and substantial cost to the City. Resources could be more efficiently allocated if there was a way to prioritize which trees were highest priority for maintenance."

![](https://lh3.googleusercontent.com/b2wuASI1KJLl8apd91J_hARRWN8UaUoEfzHzF_h4iHJXTHzz3PYtO4dEZ_kkkss-K9himRcUy4v36n16bMDNajgBKZ5ZL-WYI08UokuhcEUjYXGvNXCF2h_uR2wOXzP-EXWXSgej8f3qwx4e_YBX5nZOTfhAdnKjxKjfXFwatRwiggeMZ3tWyfpASVbu6Ak4eIVD0wAUyhu7ws9Dt6eeYN2Fmucq91nQ__CNJ6YeglrDIWwM2HwKxb3K-vgDtbaPTD5UIvQuBrXEE48DUyIOHrNP51LNiMzx4kZIInDHkduYW4D4njLwigDkBraQzzJjVymghirfZ6MMqyPQxye223RZWQD1n9qSAGdw7kTdHEbH6jZ8ozhXuM1pAF66P0YtY8cCGKqgTKAMX9knu9X7pCFnnrc_K27Vx3Ea-_oLVTg5tAJHhjt0kcBIQD3c351XhJp4lOvRB7TkFczOIt9yhFYRzv_wsgcxDu659EMoEesTHOviL5oZHOTg5RjaRNS3irDbaFN5U5QvKIl5VLjmdthV4nUGibjJWTBnNshaL57amqedEtKmZJFRPCoQYog0vmR8vJymNy9QI3P0qxk-8aHYkJkmVj8_4PSoKTWV92ZSR1YVnds8g-na8ILL8Ozk2kf66dOP67kVL_mQUOikySn74ini7RkFtj8rzL1QtzQGysqlMnfeCXI=w960-h540-no)
![](https://lh3.googleusercontent.com/e-N9lERYepyjZuHQZz7j2UXLqw5oCDSmwalfMmX3S0Dt9rcnI398lg3ECynZYElr4rMz-4LWWir8TF-JMWOY7NO1Y5qN1jdQiRzSw1dfwgYO2MNZ2yUScYAKkfNOKH5OaNIlgUET-zpIR2qTFybqB_sdkBGIj2lBGWsOpaDwVOsHugp54UcLKeP6aE2MVkhNOrbl-LGxcsoCIdgJ0o_pPinraAoobX1qgcvRkzn73fgyX5jYV5No_a1Ae34RZESNc95Mf8JiJKQmBEV2u2uJG8_wShTZjXAf_GL7P02FbhGD_hc7_dnKle_opCoTaU48-5PkAprFW3m6w69dCPCQhtp9w9_gs2dG1uI7SStqvXAsSpHCZ29xHktKqkMhCQYqQkLjA6PmOvj4GAAmAEfRam32botEo4Y1-powOCC1xo94g2AuHkL5VkoNKqgQWm5zInQDpvpvT_mVOeyPQeavNgeloU5G2WU7uW12eq9t1EPoT7irQ0utwxBzOVas_6H9VHJHKknI43VQJXhPrhs-AhIgVCRI19ZgD3m_X7ejJS_B8fz2O2RWspNWo3OjheIq3T7aDEYVQoNX2DyHbQH-UZ7ts1W-msZLPjWmcP8E8bAm4XVy21Pbgry0fyKmyNMBJmDCvm_-uuVH1Bdphn3dsyGv5NZwGJjFSjHfvURvDV_efIcTvbX_pk0=w960-h540-no)
![](https://lh3.googleusercontent.com/YGYR9z662okbZJGSnRc7rVjPeLQ9mvUJYgdFwWQIFpsHVIU6Un7jirOvvPDp1LUOy2r6WgUfgORyl7rQs9AaSVGzxiQkiQl-9_K7y1LQax2ez8nIrZcVSh_x5_47w7OOHanFeorN2YfCjiV_ME0Euwn4JiSNUyQ0fh3SoEBpd82KgvJkusS8VB-6THEWKjcf5BgVBI2Y5ltF9IMgAvk98HE17hEPmdjQKm7XvrcU9iWt_8CEi2iLL1lSHTbeGUNOpag8Dxv8-YVnyM9XovKyWYn8k2GFIZV3pdLmPFkqZWJj_5rZDcY1n-FYqK_M3z-jAP9vaXDV6skq8qnrD1qsOZRA_KUXiSV1pEPzH9XCcRYehdzUgYJEEPAr0F7MaUWvAktaptlA9kW9Pa9CNsbFt8P3JyqJLNniEPuNtG8r1fFYi0Z3ypCF-JKFN0qEg5HypP5DEZ1k3pLDXRq5hWtk9eGDHKHF4nPK3uILR7lYNNVGH9piNs54yJKFoVEzTD4RyqT-TJ4XAiR0PHK5CMam6ngCBDiN-8yuS7r6UkrCetCq-3iH2MvihMSK_LfPv7VeTmq4grsc-0XPuCSzBnDHqTc56CtUDlllCkXLqDKkodgaUEdmOtgvUpwT0S0N08-6645Xd8RfZ35DMXRVMzjkq4Vvrb7KwAl_oOfCuoTIFymUiVq8b06FZ2U=w960-h540-no)

![](./media/TreeFall_data.svg)

[TreeFall NYC](https://platform.insightdata.com/projects/treefall-nyc) by [Brianne Hendrickson-Smith](https://www.linkedin.com/in/briannekhsmith/)

- **Commentary**: New York City often has to be reactive to customer complaints, deploying public services after an event has happened. This project was focused on helping the NYC Parks department be proactive about identifying which trees in New York City were most likely to have a tree branch fall. The final solution integrated public open data from 311 citizen requests, the New York street tree census, and land cover databases. These three sources helped provide additional signal to determine which trees in which areas should be given the highest priority for maintenance. 

## Give your users actionable insight

Data scientists derive value from the ability to take amorphous problems and turn them into actionable insight that "closes the loop". Whoever your stakeholder is, you want to be able to empower your user to do something with your results. This means understanding who the target of your modeling is focused on and making conscious choices along the way with that specific user in mind. Does the result of your work allow your user to be able to actively modify their behavior in response to what you show them?

**Example**: "Staying on a diet is tough and it's estimated that only 20% of dieters stay on a regime after one month. For people on the ketogenic diet, this problem is further exacerbated by a difficulty in finding suitable keto-friendly options when choosing to eat out. The combination of a stringent dieting regime and lack of readily available nutritional information on most restaurants can spell disaster for the aspiring dieter."

![](./media/goketo.svg)

[GoKeto](https://platform.insightdata.com/projects/goketo) by [Daniel Beltran-Villegas](https://www.linkedin.com/in/daniel-beltran-villegas/)

**Commentary**: This project identified a group of users with limited choice and restricted behaviors. The final product utilized Grubhub menu information from local restaurants and nutritional information from major chain restaurants to locate meal options for ketogenic dieters based on their current location. The fellow was able to not only able to viable restaurants for dieters, but also which menu items were most keto-friendly. In doing so, this project provided dieters with a range of choices that suited their dietary lifestyles.


## Build something that works, then iterate

Data scientists in industry are often required to move quickly and meet deadlines. That means building a prototype and then iterating on it to provide improvements. One of the fastest ways to learn is through failure, and no idea is ever perfect from the start. Start with a simple solution, and then layer in the complexity.

## Avoid these common pitfalls

### Fixating on a technique or technology

When working with data, the tools and techniques you use should align with what best suits the problem. Have you ever heard someone say, "Here's some data. I don't care what you do, but can you make sure you use word2vec and Spark?" 

Yeah, I didn't think so either.

### Replicating something a company already does

Replicating an existing product or a need that is already being served does not help showcase an ability to identify new areas of exploration. Ask yourself, can you identify areas of need that are not already being covered? Users will only engage with your product if its better than what currently exists. Have a product vision  that will solve an unexplored problem.

### Starting with a data set

One of the first impulses for many people is to dig into a dataset to find something "interesting" or to a model with the highest accuracy possible. The problem here is that when you don't start with a top-down approach, you make choices that are not motivated by a problem or a user. It is then obvious to others that you have not started by thinking about the business or the issue.

<!--stackedit_data:
eyJoaXN0b3J5IjpbLTI4MjcxNzA2OSwyMTE1MjY0ODIsLTQ3Mz
kyNzI4NCwxNzQ0NTA2MjAwLC0zNTk1NjM2NzMsMTM1ODg1MTA2
NywyNjI3MTA1ODcsNjY2MjMzNzQyLC0xNjkyOTg0MDkwLDExNj
Q4MTc2NywtMTcwNDI0MTU3NV19
-->