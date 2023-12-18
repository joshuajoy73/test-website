import React, { useRef, useState } from 'react';
import './index.css';

export default function App() {
  // Create refs to store the DOM element references for buttons
  const buttonRefs = {
    no1: useRef(null),
    no2: useRef(null),
    no3: useRef(null),
    no4: useRef(null),
    no5: useRef(null),
    no6: useRef(null),
    no7: useRef(null),
    no8: useRef(null),
    

  };

  // State to manage the visibility of "hello" message
  const [showHello, setShowHello] = useState(false);
  const [showHellos,setShowHellos]=useState(false);
  const [showHelloss,setShowHelloss]=useState(false);
  const [showHellosss,setShowHellosss]=useState(false);


  // Function to handle button click
  const handleButtonClick = (buttonName) => {
    // Show/hide "hello" based on clicking the first button
    if (buttonName === 'no1') {
      setShowHello((prevShowHello) => !prevShowHello);
      setShowHellos((prevShowHellos)=>false );
      setShowHelloss((prevShowHelloss)=>false );
      setShowHellosss((prevShowHellosss)=>false );
      stateyr1((prevstateyr1)=>false);
      stateyr2((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }
    if (buttonName === 'no2') {
      setShowHellos((prevShowHello) => !prevShowHello);
      setShowHello((prevShowHellos)=>false );
      setShowHelloss((prevShowHelloss)=>false );
      setShowHellosss((prevShowHellosss)=>false );
      stateyr1((prevstateyr1)=>false);
      stateyr2((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }if (buttonName === 'no3') {
      setShowHelloss((prevShowHello) => !prevShowHello);
      setShowHello((prevShowHellos)=>false );
      setShowHellos((prevShowHelloss)=>false );
      setShowHellosss((prevShowHellosss)=>false );
      stateyr1((prevstateyr1)=>false);
      stateyr2((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }
    if (buttonName === 'no4') {
      setShowHellosss((prevShowHello) => !prevShowHello);
      setShowHello((prevShowHellos)=>false );
      setShowHelloss((prevShowHelloss)=>false );
      setShowHelloss((prevShowHellosss)=>false );
      stateyr1((prevstateyr1)=>false);
      stateyr2((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
      
    }

    
  };
  const [openyr1,stateyr1]=useState(false);
const [openyr2,stateyr2]=useState(false);
const [openyr3,stateyr3]=useState(false);
const [openyr4,stateyr4]=useState(false);

  const openmembers=(variable)=>{
    if(variable==="no5"){
      stateyr1((prevstateyr1)=>!prevstateyr1);
      stateyr2((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }
    if(variable==="no6"){
      stateyr2((prevstateyr1)=>!prevstateyr1);
      stateyr1((prevstateyr2)=>false);
      stateyr3((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }
    if(variable==="no7"){
      stateyr3((prevstateyr1)=>!prevstateyr1);
      stateyr1((prevstateyr2)=>false);
      stateyr2((prevstateyr3)=>false);
      stateyr4((prevstateyr4)=>false);
    }
    if(variable==="no8"){
      stateyr4((prevstateyr1)=>!prevstateyr1);
      stateyr1((prevstateyr2)=>false);
      stateyr2((prevstateyr3)=>false);
      stateyr3((prevstateyr4)=>false);
    }
  }

  return (
    <div className="class">
      <div className="form">
        <div className="three">
          <label className="two">MAXIMUS</label>
        </div>

        <div className="buttoncontainer">
          {}
          <button className="five" ref={buttonRefs.no1} onClick={() => handleButtonClick('no1')}>
            OUR VISION
          </button>
          <button className="hey" ref={buttonRefs.no2} onClick={() => handleButtonClick('no2')}>
            WHO WE ARE AND WHAT WE DO
          </button>
          <button className="six" ref={buttonRefs.no3} onClick={() => handleButtonClick('no3')}>
            MEMBERS
          </button>
          <button className="seven" ref={buttonRefs.no4} onClick={() => handleButtonClick('no4')}>
            CONTACT
          </button>
        </div>
      </div>
      <div className="bottom">
      <marquee className="move">WE ARE MAXIMUS!</marquee>
        {/* Display "hello" if showHello state is true */}
        <div className="members">
        {showHello && <div className="openup1">hello</div>}
        {showHellos && <div className="openup2">hi</div>}
        {showHelloss && <div className="openup3"> <button className="year-2024" onClick={()=>openmembers("no5")}>2024</button><button className="year-2025" onClick={()=>openmembers("no6")}>2025</button> <button className="year-2026"onClick={()=>openmembers("no7")}>2026</button> <button className="year-2027"onClick={()=>openmembers("no8")}>2027</button></div>}
        {showHellosss && <div className="openup4">heet</div>}
        </div>
        <div className="members">
{openyr1&&<div className="2027m">check1 </div>}
{openyr2&&<div className="2027m">check2 </div>}
{openyr3&&<div className="2027m">check3 </div>}
{openyr4&&<div className="2027m">check4 </div>}


        </div>
      
      </div>
      
    </div>
  );
}
