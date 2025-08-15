# Hi there, I'm Deepsurani! 👋

## 🚀 About Me
I'm a passionate Full-Stack Developer, UI/UX Designer, and Cinematographer/Video Editor constantly exploring new technologies and improving my skills.

## 👀 Interests
- Web Development
- Backend Technologies
- Database Management
- UI/UX Design

## 🌱 Currently Learning
- Express.js & MongoDB
- Advanced JavaScript & TypeScript
- Cloud Computing & DevOps

## 💡 Looking to Collaborate On
- Open-source projects
- Full-stack web applications
- Innovative UI/UX designs

## 📫 How to Reach Me
- GitHub: [@Deepsurani](https://github.com/Deepsurani)
- Email: deepsurani132@gmail.com

## 😄 Pronouns
He/Him

## ⚡ Fun Fact
I love solving coding challenges and designing unique user interfaces!

---
Let's build something amazing together! 🚀


cmd = new SqlCommand("SELECT vm.modelYear, CAST(vm.OverView AS NVARCHAR(MAX)) AS OverView,vm.VehicleId, vm.price, vm.SeatingCapecity, vm.VehicleName, vm.Image1, vm.image2, vm.Image3, vm.Image4, bm.Brand, vtm.VehicleType, vstm.VehicleSubtype, fm.FuleName, (SELECT STRING_AGG(ac2.AccessoriesName, ', ') FROM (SELECT DISTINCT ac.AccessoriesName FROM STRING_SPLIT(vm.AccessoriesId, ',') AS ss JOIN AccessoriesMaster ac ON ac.AccessoriesId = TRY_CAST(ss.value AS INT) WHERE ss.value <> '') AS ac2) AS Accessoriname FROM VehicleMaster AS vm INNER JOIN BrandMaster AS bm ON vm.BrandId = bm.BrandId INNER JOIN VehicleTypeMaster AS vtm ON vm.VehicleTypeId = vtm.VehicleTypeId INNER JOIN VehicleSubtypeMaster AS vstm ON vm.VehicleSubtypeId = vstm.VehicleSubtypeId INNER JOIN FuleMaster AS fm ON vm.FuleId = fm.FuleId;", con);
            
