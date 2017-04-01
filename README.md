第一次修改

修改内容

var selectedNumOrderBlood = function (orderId) {<br/>
            for (var i = 0; i < $scope.cpOrderBloodList.length; ++i) {<br/>
                var cpBloodMaster = $scope.cpOrderBloodList[i];<br/>
                if (orderId === getBloodOrderId(cpBloodMaster)) {<br/>
                    return cpBloodMaster;
                }<br/>
            }<br/>
            return null;<br/>
        }<br/>
