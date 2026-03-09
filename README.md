kubectl get pods,svc -n dev
<img width="930" height="207" alt="Screenshot 2026-03-09 193622" src="https://github.com/user-attachments/assets/5abdf03b-4896-4e1a-bd9f-0dfa6ab5d2e7" />

kubectl get pods,svc -n staging
<img width="935" height="202" alt="Screenshot 2026-03-09 193643" src="https://github.com/user-attachments/assets/8bc857ce-c22b-45d4-85c4-28a9da6142e5" />

kubectl port-forward pod/frontend-pod 8082:80 -n dev
<img width="924" height="510" alt="Screenshot 2026-03-09 193738" src="https://github.com/user-attachments/assets/57cf0814-3cb8-4dfa-b3e3-7706dfa6a6b9" />
