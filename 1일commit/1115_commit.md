# 11/15 **커밋 내용**

---

## 11/15 화**요일**

43번째 커밋

import { Dimensions } from "react-native";
import styled from "styled-components/native";
 
const StyledInput = styled.TextInput`
    // Component를 생성할 때 전달받은 width로 input의 크기를 설정한다.
    width: ${({ width }) => width - 40}px;
    // 생략
`;
 
const Input = () => {
    const width = Dimensions.get("window").width;
    return (
        <StyledInput
            width={width}
            // ... 생략됨
        />
    );
}