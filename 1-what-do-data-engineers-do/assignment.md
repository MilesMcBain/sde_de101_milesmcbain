# Enabling Data Analytics

> Imagine that you are hired to enable data analytics; where would you start?
> How would you go about gathering requirements? Hint: Think backward from what
> the business may need. Share your assignment with me by creating a repo (like
> this one if you haven't already) and writing down your notes/code under the
> folder for lesson 1.

I think to do this effectively you need to be engaging across many
levels of the business. There may be some pre-decided aspects of what you have
to do that can simplify things, but assuming there isn't we would have to consult:

## 1. Leadership

    - What is their vision for the project? 
    - What is motivating it? 
    - What are they trying to unlock? 
    - What does success look like?

## 2. Mangers

    - What are the project budget / time-frames / resources etc?
    - In there anything that is definitely off the table, or perhaps almost certainly off the table?
      - E.g. any ghosts of data engineers past that will haunt the project?
        - "They tried that back in '07, it didn't work then and it won't work now"
    - Who are the stakeholder groups we need to consult and what are their business functions?

## 3. Stakeholder Groups

    - What are the critical sources of data that are currently used to support your function?
      - What are the business concepts they represent?
      - How large are they (bytes / rows)?
      - How fresh do they need to be (yearly, monthly, weeks, daily, hourly, real-time)?
    - What type of products do you build from them?
        - Who consumes those products?
          - And via what media?
        - Are they internal or external facing?
        - Do those products expose access to the underlying data?
    - Can you walk me through the data acquisition phase of a project you're currently working on?
    - What tools do you use?
      - "We're a Python/R/PowerBI shop."
    - On what platform (hardware or environment) do you process data now?
      - What constraints do you actively have to manage around?
        - Processing time?
        - Memory usage?
        - Disk usage?
        - Budget?
        - Cat on the keyboard?
    - What capabilities do you hope to acquire in the future and are there any datasets real or fictional that would support them?
      - "If we just had X then we could do Y"
      - What datasets are X?
    - Do you any of the datasets you use contain personally identifying information, or other sensitive information?
      - Is that information necessary for your products?

## 4. Bureaucracy (IT, Legal, Cybersecurity etc)

    - Does any part of this project fall under your remit and require your approval?
      - How can I get the necessary approvals?
    - Do you have any concerns?
      - Is there anything that is definitely off the table?
    - Are there any policies, or laws that would affect how sensitive datasets can be combined, stored, moved around, shared?
    - What kind of permissions controls are required?  
    - What level of access logging is required? 
      - Do you have preferred formats or tools you work with that would decide how this information is stored?

