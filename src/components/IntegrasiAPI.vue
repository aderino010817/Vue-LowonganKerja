<template>
    <div class="bodypad">
        <div class="flexrow">
            <div class="flexcolumn">
                <div class="marketingPlanner SeeJob">Marketing Planner
                    <button>See Job</button>
                </div>
                <div class="contentPlan SeeJob">UI/UX Content Planner
                    <button>See Job</button>
                </div>
                <div class="HrLegal SeeJob">HR/Legal Manager
                    <button>See Job</button>
                </div>
            </div>
            <div class="flexcolumn">
                <div class="SeeJob">UI/UX Content Writer
                    <button>See Job</button>
                </div>
                <div class="SeeJob">UI/UX Content Designer
                    <button>See Job</button>
                </div>
                <div class="SeeJob">Java Springboot
                    <button>See Job</button>
                </div>
            </div>
        </div>
        <div class="additional">
        <div class="bonuspad">
            <h1 class="title">Marketing Planner</h1>
            <h2 class="jobdesc">Job Description :</h2>
            <ul>
                <li>Monitor Competition to identify new Industry trends and opportunities for innovation</li>
                <li>Develope Marketing strategies based on customer preferences, business objective, and available resource
                </li>
                <li>Conduct market research to identify potential customers and assess their needs, interest, and
                    preferences</li>
                <li>Work with design teams to develope </li>
                <li>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Molestiae, iusto tempora obcaecati voluptates
                    exercitationem rem, minima explicabo in, enim reiciendis tenetur aliquam? Error ad cumque natus,
                    provident aliquid enim tempore?</li>
            </ul>
            <h2 class="skill">Skill :</h2>
            <ul>
                <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Qui commodi asperiores reiciendis odit
                    expedita, molestias labore, officiis, enim perferendis a recusandae aliquam iure quam. Facilis quibusdam
                    nihil beatae dignissimos ullam.</li>
                <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse quis commodi cum labore iste nesciunt
                    velit in optio, voluptatum recusandae molestias perferendis nostrum id ducimus temporibus autem omnis
                    accusamus sapiente.</li>
                <li>Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis quae omnis ab nemo aperiam recusandae
                    quis corporis fuga, blanditiis nobis debitis laudantium hic iste tempora. Reprehenderit unde optio
                    officia consectetur?</li>
                <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Libero, et expedita quam consequuntur itaque
                    corporis est eaque tenetur a maiores obcaecati deserunt ab ipsam quis nostrum nisi? Eaque, unde minus?
                </li>
                <li>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Libero, et expedita quam consequuntur itaque
                    corporis est eaque tenetur a maiores obcaecati deserunt ab ipsam quis nostrum nisi? Eaque, unde minus?
                </li>
            </ul>
        </div>
        <h1>Send Your Job Application</h1>
        <form>
            <div class="formRow">
                <div class="formColumn">
                    <div class="inputColumn">
                        <label id="name" class="labelForm">Your Name</label>
                        <input class="inputForm" type="text" placeholder="Enter Your Name" for="name">
                    </div>
                    <div class="inputColumn">
                        <label id="email" class="labelForm">Email Address</label>
                        <input class="inputForm" type="email" placeholder="Enter Your Email" for="email">
                    </div>
                </div>
                <div class="formColumn">
                    <div class="inputColumn">
                        <label id="name" class="labelForm">Mobile Number</label>
                        <input class="inputForm" type="text" placeholder="Enter Your Phone Number" for="name">
                    </div>
                    <div class="inputColumn">
                        <label id="name" class="labelForm">Write Your Message here...</label>
                        <input class="inputForm" type="text" for="name" placeholder="Write Your Message">
                    </div>
                </div>
            </div>
            <div class="flexColumnFile">
                <h2>File</h2>
                <img src="../assets/vue.svg" type="input"/>
                <input type="file" placeholder="Upload Your File" alt="Upload" />
            </div>
            <button class="button">Send Message</button>
        </form>
    </div>
    </div>
</template>
<style>
.button {
    margin-left: 3em;
    color: white;
    background-color: gray;
    border: 1px solid gray;
    box-shadow: 1px 1px 3px 1px gray;
    width: 170px;
    font-size: 20px;
    border-radius: 5px;
    padding: 10px;
}
.flexColumnFile img {
    width: 33px;
    display: flex;
    flex-direction: column;
    margin-left: 1.5em;
}
.formColumn input {
    border: 1px solid gainsboro;
    box-shadow: 1px 1px 3px 1px gray;
    border-radius: 8px;
    
}
.flexColumnFile {
    display: flex;
    flex-direction: column;
    gap: 10px;
    justify-content: center;
    padding: 3em;;

}
.inputForm {
    padding: 10px;
    border: 1px solid gainsboro;
}

.labelForm {
    font-weight: 700;
    font-size: 24px;
}

.formRow {
    display: flex;
    flex-direction: row;
    justify-content: space-around;
    width: 100%;
}

.formColumn {
    display: flex;
    width: 40%;
    flex-direction: column;
    gap: 5px;
}

.inputColumn {
    display: flex;
    flex-direction: column;
    gap: 5px;
}

.bonuspad .title {
    color: green;
}

.bonuspad {
    padding: 2em;
}

.bodypad {
    padding: 3em;
}

.flexrow {
    display: flex;
    flex-direction: row;
    justify-content: center;
    width: 100%;
    gap: 30px;
}

.flexcolumn {
    display: flex;
    flex-direction: column;
    gap: 10px;
    width: 50%;
}

.SeeJob button {
    background-color: orange;
    color: white;
    padding: 5px;
    border: 1px solid gainsboro;
    border-radius: 4px;
    width: 90px;
    height: 30px;
    font-weight: 800;
}
.additional {
    background-color: gainsboro;
    margin-bottom: 2em;
    padding: 1em;
    margin-top: 1em;
    border: 1px solid gainsboro;
    border-radius: 8px;
    box-shadow: 2px 2px 4px 2px gainsboro;
}
.SeeJob {
    color: green;
    background-color: gainsboro;
    padding: 1em;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    box-shadow: 2px 2px 4px 2px gray;
    border-radius: 8px;
}
</style>