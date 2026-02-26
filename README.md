<div align= "center">
    <img src="https://capsule-render.vercel.app/api?type=cylinder&color=auto&height=120&text=K8S와%20ansible을%20이용한%20간단한%20app%20배포&animation=&fontColor=000000&fontSize=30" />
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 개요 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;"> <p>ROSA 환경에서 TEKTON을 이용하여 자동 배포를 구성했습니다. 예전 기술인 DeploymentConfig를 사용해보고 싶어 DC를 사용해 구성해봤습니다. </div> 
    </div>
    <br>

<div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> Architecture </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;">
      <p>!달라진 부분이 조금 있습니다!</p>
      <img width="600" height="430" alt="image" src="https://github.com/user-attachments/assets/cfa82525-e77e-4ca6-83c0-e3272fa0b07c" />
    </div> 
    </div>
    <br>

<div align= "center">
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ Tech Stacks </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;"> <li>ROSA</li> <li>OpenShift</li> <li>Tekton</li> <li>Github</li> <li>Route53</li> <li>CloudFront </div> 
    </div>
    <br>
    
<div align= "center">
    </div>
    <div style="text-align: left;"> 
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 주요 구축 내용 </h2>  
    <div style="font-weight: 700; font-size: 15px; text-align: left; color: #282d33;">
      <li>ROSA 환경에서 app 배포를 DeploymentConfig를 사용하여 자동화(git tag push시에 자동으로 재배포)</li>
      <li>HPA를 이용한 AutoScaling 구성 및 Route 구성</li>
    </div> 
    </div>


