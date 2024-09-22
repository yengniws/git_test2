<div align="center">

<table>
  <tbody>
    <tr align="center">
      <td colspan="3">
        SKHU IT 경진대회 출품작 <br/> Team Hoodie Backend
      </td>
    </tr>
    <tr align="center">
      <td colspan="3">
        <h3>* OTTi *</h3>
      </td>
    </tr>
    <tr align="center">
      <td colspan="3">
        <img src="https://otti-bucket-2024.s3.ap-northeast-2.amazonaws.com/otti-image/otti.png" width="50%"/>
      </td>
    </tr>
    <tr align="center">
      <td colspan="3">OTT 구독료 관리를 효율적으로 지원하고,<br/>사용자 간의 공동 구독 기능을 제공하는 사용자 중심의 앱</td>
    </tr>
    <tr>
      <td align="center">
        <strong>Project Resources</strong>
      </td>
      <td rowspan="9"></td> <!-- 빈 열 추가 -->
      <td align="center"><strong>목차</strong></dh>
    </tr>
    <tr>
      <td align="center"><a href="">View in Web</a></td>
      <td align="center">
        <a href="#-team-hoodie">Team Hoodie?</a> <br/>
      </td>
    </tr>
    <tr>
      <td align="center"><a href="">Download mobile app</a></td>
      <td align="center">
        <a href="#-작품-개요">작품 개요</a> <br/>
      </td>
    </tr>
    <tr>
      <td align="center"><a href="https://otti-hoodie.duckdns.org/swagger-ui/index.html#/">Documentation</a></td>
      <td align="center">
        <a href="#작품-구성">작품 구성</a> <br/>
      </td>
    </tr>
    <tr>
      <td></td>
      <td align="center">
        <a href="#%EF%B8%8F-기술-스택">기술 스택 & 서버 아키텍쳐</a> <br/>
      </td>
    </tr>
    <tr>
      <td></td>
      <td align="center">
        <a href="#database-erd">Database ERD</a> <br/>
      </td>
    </tr>
    <tr>
      <td></td>
      <td align="center">
        <a href="#-주요-개발-방법">주요 개발 방법</a> <br/>
      </td>
    </tr>
    <tr>
      <td></td>
      <td align="center">
        <a href="#-프로젝트-확장성">프로젝트 확장성</a> <br/>
      </td>
    </tr>
    <tr>
      <td></td>
      <td align="center">
        <a href="#-team-of-hoodie">Team of Hoodie</a> <br/>
      </td>
    </tr>
  </tbody>
</table>


<hr/>

## 👕 Team Hoodie?

팀원 모두가 후드를 착용하고 있었던 당시의 모습에서 영감을 받아,<br/>창의적이고 자유로운 협업의 의지를 담고 있음.<br/>'Hoodie'라는 이름은 이러한 팀의 정체성을 반영하며,<br/>협업의 분위기를 강조함. | <img src="https://github.com/user-attachments/assets/43edf6c0-0874-4e02-afbf-852765dfb6ba" alt="Team Hoodie" width="150">
---|---|

<br/><br/>

## 🧐 작품 개요
  <blockquote align="left">
	  본 작품은 OTT 구독료 관리의 불편함을 해결하기 위해 개발됨.<br/> 
	  매달 OTT 구독료의 자동이체 시점을 기억하기 어렵고,<br/> 
	  갑작스럽게 통장에서 인출되는 구독료의 출처를 잊어버리는 경우가 빈번하다는 의견에서 출발함.<br/> 
	  <br/> 
	  이를 해결하기 위해 사용자는 OTT 구독 정보를 저장하고 구독료의 출금 일정을 캘린더와 파이 차트, 디데이 기능을 통해 시각적으로 확인할 수 있음.<br/> 
	  또한, '팟' 기능을 도입하여 팀원을 모집하고 OTT 구독료를 공동으로 분담할 수 있도록 함.<br/> 
	  사용자는 각자의 조건을 작성하여 팀원을 찾는 게시글을 올릴 수 있으며,<br/> 
	  이를 통해 넷플릭스와 같은 여러 계정을 함께 사용할 수 있는 기회를 제공함.<br/> 
	  이러한 기능은 사용자 간의 협업을 촉진하고, OTT 구독료 관리의 효율성을 높임.<br/> 
	  <br/> 
	  유사한 앱으로는 피클플러스와 링키드가 있음. 두 앱은 주로 구독 서비스를 공유하는 멤버를 찾는 기능에 중점을 두고 있음.<br/> 
	  반면, 본 작품은 구독료 공동 분담 기능을 서브 기능으로 두고, 메인 기능으로는 사용자가 자신의 OTT 구독 스케줄을 한눈에 보고 기억할 수 있도록 돕는 점에서 차별성을 가짐.
	  <br/> 구독료 출금 일정을 시각적으로 관리하고, 사용자가 일정 관리를 보다 체계적으로 할 수 있도록 설계된 것이 이 앱의 주요 강점임.<br/> 
  </blockquote>
<br/><br/>

## 📑작품 구성
<table>
    <thead>
        <tr>
            <th>기능</th>
            <th>상세 기능</th>
            <th>설명</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><strong>소셜 로그인</strong></td>
            <td>카카오 OAuth를 활용한 간편한 소셜 로그인 기능</td>
            <td>사용자가 손쉽게 계정을 생성하고 로그인할 수 있음</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="2"><strong>구독료 관리</strong></td>
            <td>총 구독료 확인</td>
            <td>이번 달 기준으로 사용자가 지출한 OTT 구독료를 한눈에 볼 수 있도록 표시</td>
        </tr>
        <tr>
            <td>한 번에 보기</td>
            <td>구독 중인 OTT 서비스들의 결제 날짜를 캘린더로 시각화하여 쉽게 파악할 수 있도록 함</td>
        </tr>
        <tr>
            <td rowspan="2"><strong>캘린더 기능</strong></td>
            <td>결제 날짜 표시</td>
            <td>달력에 구독 서비스의 결제 날짜를 표시하고, 특정 날짜를 클릭하면 해당 OTT 서비스의 구독 정보를 상세히 확인할 수 있는 모달창이 뜸</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="2"><strong>구독 OTT 추가 및 <br/> 관리 기능</strong></td>
            <td>사용자가 구독 중인 OTT 서비스 추가</td>
            <td>넷플릭스, 웨이브, 티빙, 쿠팡플레이, 디즈니플러스, 왓챠의 요금제, 결제 금액, 결제일 등을 입력 및 수정할 수 있음</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="2"><strong>구독 정보 관리</strong></td>
            <td>구독 정보 전체 확인</td>
            <td>사용자의 구독 정보 전체를 한눈에 확인할 수 있으며, 요금제, 결제 금액, 결제일, 메모 등을 수정하거나 삭제 가능</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="4"><strong>알림 기능</strong></td>
            <td>OTT 구독료 납부일 알림</td>
            <td>3일 전에 알람을 보내 구독료 납부를 잊지 않도록 도와줌</td>
        </tr>
        <tr>
            <td>읽지 않은 알림 확인</td>
            <td>사용자는 읽지 않은 알림을 한눈에 확인할 수 있으며, 팟 기능 관련 알림도 포함됨</td>
        </tr>
        <tr>
            <td>팟 신청 알림</td>
            <td>팟을 생성한 사용자에게는 팟 신청 알림이 전송되며, 팟 신청이 승인되거나 거절될 경우 해당 내용에 대한 알림이 신청자에게 전달됨</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="3"><strong>프로필 관리</strong></td>
            <td>프로필 사진, 닉네임 수정</td>
            <td>사용자는 프로필 사진, 닉네임을 수정할 수 있으며, 기본 프로필 사진은 오띠 로고로 설정됨</td>
        </tr>
        <tr>
            <td>로그아웃 및 계정 탈퇴 기능</td>
            <td>로그아웃, 계정 탈퇴 기능도 제공</td>
        </tr>
        <tr>
        </tr>
        <tr>
            <td rowspan="4"><strong>팟(Pot) 기능</strong></td>
            <td>팀원 모집 및 구독료 공동 분담</td>
            <td>사용자가 팀원을 모집해 구독료를 공동으로 분담할 수 있는 기능</td>
        </tr>
        <tr>
            <td>팟 만들기</td>
            <td>사용자가 원하는 OTT 서비스 및 요금제를 선택하고, 입금 계좌 및 결제일을 설정할 수 있음</td>
        </tr>
        <tr>
            <td>팟 신청 리스트</td>
            <td>팟에 지원한 사용자 목록을 확인하고, 각 지원자의 프로필 사진, 닉네임, 한 줄 소개를 볼 수 있음</td>
        </tr>
        <tr>
            <td>팟 관리</td>
            <td>팟 멤버 목록 확인, 방장의 멤버 관리(강퇴 가능), 공지 사항 작성 등의 기능을 제공</td>
        </tr>
        <tr>
            <td rowspan="2"><strong>게시글 관리</strong></td>
            <td>작성한 글 목록 확인</td>
            <td>사용자가 작성한 글 목록을 확인하고, 글 제목, 내용 미리보기, 댓글 개수 등의 정보를 확인할 수 있음</td>
        </tr>
        <tr>
            <td>글 작성, 수정, 삭제 및 <br> 사진 추가</td>
            <td>글을 작성하거나 수정, 삭제할 수 있으며, 글에 사진을 추가할 수 있음</td>
        </tr>
    </tbody>
</table>

---

<table>
  <tbody>
    <tr>
      <td align="center">
        <h2>🛠️ 기술 스택</h2>
        <div align="center">
          <table style="width: 100%; table-layout: fixed;">
            <thead>
              <tr>
                <th>Role</th>
                <th>Stack</th>
              </tr>
            </thead>
            <tbody>
              <tr>
                <td rowspan="5">FE</td>
                <td><img src="https://img.shields.io/badge/react-61DAFB?style=flat-square&logo=react&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/styledcomponents-DB7093?style=flat-square&logo=styledcomponents&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/typescript-3178C6?style=flat-square&logo=typescript&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/axios-5A29E4?style=flat-square&logo=axios&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/vercel-000000?style=flat-square&logo=typescript&logoColor=white"/></td>
              </tr>
              <tr>
                <td rowspan="4">BE</td>
                <td><img src="https://img.shields.io/badge/JAVA-007396?style=flat-square&logo=java&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/springboot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/mysql-4479A1?style=flat-square&logo=mysql&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/swagger-85EA2D?style=flat-square&logo=swagger&logoColor=white"></td>
              </tr>
              <tr>
                <td rowspan="2">Infra</td>
                <td><img src="https://img.shields.io/badge/amazon-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/amazons3-569A31?style=flat-square&logo=amazons3&logoColor=white"/></td>
              </tr>
              <tr>
                <td rowspan="2">App</td>
                <td><img src="https://img.shields.io/badge/React Native-61DAFB?style=flat-square&logo=React&logoColor=black"/></td>
              </tr>
              <tr>
                <td><img src="https://img.shields.io/badge/expo-000020?style=flat-square&logo=expo&logoColor=white"/></td>
              </tr>
            </tbody>
          </table>
        </div>
      </td>
      <td align="center">
        <h2>🏛️ 서버 아키텍쳐</h2>
        <img src="">
      </td>
    </tr>
  </tbody>
</table>

---

## 🗄Database ERD
<img src="https://github.com/user-attachments/assets/bb7cee13-90bd-4b93-8ebb-96c087d26fe5" width=650>

---

## 💻 주요 개발 방법

<table>
  <tbody>
    <tr>
      <td colspan="4" align="center">FE</td>
    </tr>
    <tr>
      <td rowspan="2">김주하</td>
      <td>
        <strong>커뮤니티 작성 글 및 댓글</strong><br/>
        <img src="" /><br/>
        <details>
          <summary>설명</summary>
          <div markdown="1">
            - 팟의 방장 권한을 가진 사람이 작성한 ‘커뮤니티 글’ 기능임.<br/>
            - 팟에 함께할 사람을 모집하고, 사람들은 모집글을 보고 신청할 수 있음.<br/>
            - 하단에는 참여 의사나 문의를 남길 수 있는 댓글 기능이 있음.<br/>
            - 댓글을 남긴 사람의 닉네임을 api를 통해 가져오고, 댓글의 내용을 post 메소드를 활용해 db로 넘김.<br/>
            - 작성 시기는 사용자가 댓글 추가를 누른 순간을 기준으로 프론트에서 경과 시간을 분 단위로 계산하여 보여줌.
          </div>
        </details>
      </td>
      <td rowspan="2">박예은</td>
      <td>
        <strong>ott 추가, 삭제, 구독 정보 리스트</strong><br/>
        <img src="" /><br/>
        <details>
          <summary>설명</summary>
          <div markdown="1">
            - 메인 페이지 속 ‘구독 추가’ 버튼 또는 ‘+’ 버튼을 통해 ott 추가 페이지로 이동함.<br/>
            - 추가하고 싶은 ott의 이름을 select 창을 통해 선택하면, 해당 ott의 아이콘 이미지가 자동으로 선택되고, 해당 ott의 요금제 종류들이 ‘요금제 선택’란의 select option으로 삽입됨.<br/>
            - 모든 값이 입력이 된 상태에서(메모 칸 제외) ‘등록하기’ 버튼을 누르면 ‘등록되었어요!’라는 토스트 메세지와 함께 정보가 post 메소드를 통해 db로 넘어가고, 메인 화면으로 이동함.<br/>
            - 만약 모든 값이 입력이 되지 않았다면 '등록에 실패했어요.’라는 토스트 에러 메세지가 뜸.<br/>
            - 메인 화면에서는 등록된 ott 정보들을 리스트로 보여주며, get 메소드를 통해 백엔드 api를 통해 불러옴. 해당 리스트는 map 함수를 이용해 subscriptions 배열에 담긴 구독 정보의 개수만큼 항목을 생성함.<br/>
            - 구독 리스트의 항목 중 상세 정보를 보고 싶은 항목을 누르면 해당 구독 항목의 ‘구독 정보’ 페이지로 이동되고, 내가 작성한 구독 정보를 확인할 수 있음.<br/>
            - ‘구독 정보’ 페이지 속 ‘수정하기’ 버튼을 누르면 각 항목이 수정 가능한 인풋 창으로 변경되며(editing 상태),<br/>
            수정 완료 후 ‘저장하기’ 버튼을 누르면 ‘수정 되었습니다!’라는 토스트 메세지와 함께 setEditing(false) 상태로 변경되어 초기 진입 페이지와 같은 화면(수정이 불가능한 구독 정보 페이지)이 보임. (변경된 내용은 put 메소드로 db에 전송됨)<br/>
            - ‘구독 정보’ 페이지 속 ‘삭제하기’ 버튼을 누르면 '삭제 되었습니다!’라는 토스트 메세지와 함께 delete 메소드를 통해 db로 전송되고, 메인 페이지로 이동함.
          </div>
        </details>
      </td>
    </tr>
    <tr>
      <td>
        상세 코드
      </td>
      <td>
        상세코드
        <details>
          <summary>구독 리스트를 보여주는 컴포넌트</summary>
          <div markdown="1">
<pre>
  
  // SubscriptionList.tsx

  const SubscriptionBox: React.FC<{ subscription: Subscription }> = ({
    subscription,
  }) => {
    const navigate = useNavigate();
    const [dday, setDday] = useState<number | null>(null);
    useEffect(() => {
      const fetchDday = async () => {
        try {
          const response = await axiosInstance.get<DDayResponse>(
            `/api/subscription/d-day/${subscription.id}`,
          );
          setDday(response.data.dday);
        } catch (error) {
          console.error('D-Day 정보를 불러오기 중 에러:', error);
        }
      };
      fetchDday();
    }, [subscription.id]);
    const handleClick = () => {
      navigate(`/main/subscriptionDetail/${subscription.id}`);
    };
    return (
      <S.ListContentBox onClick={handleClick}>
        <S.ListImageWrap>
          <S.ListImage
            src={subscription.ott.image}
            alt={`${subscription.ott.name} logo`}
          />
        </S.ListImageWrap>
        <S.ListTxtBox>
          <S.ListTxtTitle>{subscription.name}</S.ListTxtTitle>
          <S.ListTxts>{subscription.ott.ratePlan} 요금제</S.ListTxts>
          <S.ListTxts>{subscription.payment}원</S.ListTxts>
        </S.ListTxtBox>
        <S.ListDDayContainer>
          <S.ListDDayTxt>
            {dday !== null ? (dday === 0 ? 'D-Day' : `D - ${dday}`) : 'null'}
          </S.ListDDayTxt>
        </S.ListDDayContainer>
      </S.ListContentBox>
    );
  };

  const SubscriptionList: React.FC = () => {
    const [subscriptions, setSubscriptions] = useState<Subscription[]>([]);
    const navigate = useNavigate();
    useEffect(() => {
      const fetchSubscriptions = async () => {
        try {
          const response = await axiosInstance.get('/api/subscription/user');
          setSubscriptions(response.data);
          // console.log(response.data);
        } catch (error) {
          console.error('구독 정보 불러오기 오류:', error);
        }
      };
      fetchSubscriptions();
    }, []);
    const handleAddOtt = () => {
      navigate('/main/addOttSubscription');
    };
    return (
      <>
        <S.ListContainer>
          <S.ListTitleWrap>
            <S.ListTitle>구독 중인 OTT</S.ListTitle>
            <IoAddCircle size={20} onClick={handleAddOtt} />
          </S.ListTitleWrap>
          {subscriptions.map((subscription) => (
            <SubscriptionBox key={subscription.id} subscription={subscription} />
          ))}
          <S.ButtonWrap>
            <S.AddOttBtn onClick={handleAddOtt}>+ 구독 추가</S.AddOttBtn>
          </S.ButtonWrap>
        </S.ListContainer>
      </>
    );
  };

  export default SubscriptionList;
</pre>
          </div>
        </details>
        <details>
          <summary>ott 구독 정보를 추가하는 페이지</summary>
          <div markdown="1">
<pre>
//AddOttSubscription.tsx

const AddOttSubscription: React.FC = () => {
  const [ott, setOtt] = useState(ottOptions[0]);
  const [name, setName] = useState('');

  const [plan, setPlan] = useState(ottOptions[0].rate_plans[0]);

  const [amount, setAmount] = useState('');
  const [date, setDate] = useState('1');
  const [memo, setMemo] = useState('');

  const handleOttChange = (selectedOttName: string) => {
    const selectedOtt =
      ottOptions.find((option) => option.ott_name === selectedOttName) ||
      ottOptions[0];
    setOtt(selectedOtt);
    setPlan(selectedOtt.rate_plans[0]);
  };

  const handleAmountChange = (e: React.ChangeEvent<HTMLInputElement>) => {
    const value = e.target.value;
    if (/^\d*$/.test(value)) {
      setAmount(value);
    }
  };

  const handleSubmit = async () => {
    if (!name || !amount) {
      toast.error('모든 값을 입력해주세요!');
      return;
    }

    try {
      // const userId = localStorage.getItem('user_id'); // 유저 ID를 로컬 스토리지에서 가져옴

      await axiosInstance.post('/api/subscription', {
        name: name,
        payment: Number(amount),
        memo: memo,
        paymentDate: Number(date),
        //userId: Number(userId),
        ottName: ott.ott_name,
        ottRatePlan: plan,
      });

      toast.success('등록되었어요!', {
        onClose: () => {
          window.location.href = '/main';
        },
        autoClose: 1500,
      });
    } catch (error) {
      console.error('정보 저장 중 에러 발생', error);
      toast.error('등록에 실패했어요.');
    }
  };

  const dateOptions = Array.from({ length: 31 }, (_, i) => i + 1);

  return (
    <S.AddOttWrapper>
      <S.TitleWrapper>
        <NewTopBar title="OTT 추가" />
      </S.TitleWrapper>
      <S.Container>
        <S.Header>
          <S.Image src={ott.ott_image} alt={ott.ott_name} />
          <S.SelectOttName
            value={ott.ott_name}
            onChange={(e) => handleOttChange(e.target.value)}
          >
            {ottOptions.map((option) => (
              <option key={option.ott_name} value={option.ott_name}>
                {option.ott_name}
              </option>
            ))}
          </S.SelectOttName>
        </S.Header>
        <S.Section>
          <S.Label>이름</S.Label>
          <S.Input value={name} onChange={(e) => setName(e.target.value)} />
        </S.Section>
        <S.Divider />
        <S.Section>
          <S.Label>요금제 선택</S.Label>
          <S.Select value={plan} onChange={(e) => setPlan(e.target.value)}>
            {ott.rate_plans.map((plan) => (
              <option key={plan} value={plan}>
                {plan}
              </option>
            ))}
          </S.Select>
        </S.Section>
        <S.Divider />
        <S.Section>
          <S.Label>구독료</S.Label>
          <S.Input value={amount} onChange={handleAmountChange} />
        </S.Section>
        <S.Divider />
        <S.Section>
          <S.Label>정기결제일</S.Label>
          <S.Select value={date} onChange={(e) => setDate(e.target.value)}>
            {dateOptions.map((day) => (
              <option key={day} value={day.toString()}>
                {`${day}일`}
              </option>
            ))}
          </S.Select>
        </S.Section>
        <S.Divider />
        <S.LabelMemo>메모</S.LabelMemo>
        <S.MemoBox>
          <S.InputMemo value={memo} onChange={(e) => setMemo(e.target.value)} />
        </S.MemoBox>
        <S.ButtonContainer>
          <S.ButtonSave onClick={handleSubmit}>등록하기</S.ButtonSave>
        </S.ButtonContainer>
      </S.Container>
    </S.AddOttWrapper>
  );
};

export default AddOttSubscription;
</pre>
  </div>
        </details>
        <details>
          <summary>구독 상세 정보 페이지 (+수정, 삭제 포함)</summary>
          <div markdown="1">
            <pre>
              //SubscriptionDetail.tsx

const SubscriptionDetail: React.FC = () => {
  const { id } = useParams<{ id: string }>();
  const navigate = useNavigate();
  const [subscription, setSubscription] = useState<Subscription | null>(null);
  const [editing, setEditing] = useState(false);
  const [formData, setFormData] = useState({
    name: '',
    payment: 0,
    memo: '',
    paymentDate: 1,
    ott: {
      id: 0,
      name: '',
      ratePlan: '',
      price: 0,
      image: '',
      createdDate: '',
      modifiedDate: '',
    },
  });

  const [isLoading, setIsLoading] = useState(false);

  useEffect(() => {
    const fetchSubscription = async () => {
      try {
        const response = await axiosInstance.get(`/api/subscription/${id}`);
        setSubscription(response.data);
        setFormData(response.data);
      } catch (error) {
        console.error('데이터 가져오는 중 에러:', error);
      }
    };
    fetchSubscription();
  }, [id]);

  const handleDelete = () => {
    axiosInstance
      .delete(`/api/subscription/${id}`)
      .then(() => {
        toast.success('삭제 되었습니다!');
        setTimeout(() => {
          navigate('/main');
        }, 1000);
      })
      .catch((error) => console.error('데이터 삭제 중 오류:', error));
  };

  const handleSave = () => {
    const payload = {
      name: formData.name,
      payment: formData.payment,
      memo: formData.memo,
      paymentDate: formData.paymentDate,
      ottName: formData.ott.name,
      ottRatePlan: formData.ott.ratePlan,
    };
    axiosInstance
      .put(`/api/subscription/${id}`, payload)
      .then((response) => {
        setSubscription(response.data);
        toast.success('수정되었습니다!');
        setEditing(false);
        setIsLoading(true);
        // 페이지 새로고침
        setTimeout(() => {
          window.location.reload();
        }, 1000);
      })
      .catch((error) => console.error('데이터 업데이트 중 에러:', error));
  };

  if (isLoading) {
    return <LoadingPage />;
  }

  const handleChange = (
    e: React.ChangeEvent<HTMLInputElement | HTMLSelectElement>,
  ) => {
    const { name, value } = e.target;
    if (name.startsWith('ott.')) {
      const [_, key] = name.split('.');
      setFormData((prevFormData) => ({
        ...prevFormData,
        ott: {
          ...prevFormData.ott,
          [key]: value,
        },
      }));
    } else {
      setFormData((prevFormData) => ({
        ...prevFormData,
        [name]:
          name === 'payment' || name === 'paymentDate'
            ? value === ''
              ? 0
              : parseInt(value)
            : value,
      }));
    }
  };

  return (
    <S.OttDetailWrapper>
      <S.TitleWrapper>
        <NewTopBar title="구독 정보" />
      </S.TitleWrapper>
      <S.Container>
        {subscription && (
          <>
            <S.Header>
              <S.Image
                src={formData.ott?.image || ''}
                alt={formData.ott?.name || 'OTT 이미지'}
              />
              {editing ? (
                <S.SelectOttName
                  name="ott.name"
                  value={formData.ott?.name || ''}
                  onChange={handleChange}
                >
                  {ottOptions.map((option) => (
                    <option key={option.name} value={option.name}>
                      {option.name}
                    </option>
                  ))}
                </S.SelectOttName>
              ) : (
                <S.OttName>{subscription.ott?.name}</S.OttName>
              )}
            </S.Header>
            <S.Section>
              <S.Label>이름</S.Label>
              {editing ? (
                <S.Input
                  name="name"
                  value={formData.name}
                  onChange={handleChange}
                />
              ) : (
                <S.Text>{subscription.name}</S.Text>
              )}
            </S.Section>
            <S.Divider />
            <S.Section>
              <S.Label>요금제</S.Label>
              {editing ? (
                <S.Select
                  name="ott.ratePlan"
                  value={formData.ott?.ratePlan || ''}
                  onChange={handleChange}
                >
                  {ottOptions
                    .find((option) => option.name === formData.ott?.name)
                    ?.plans.map((plan) => (
                      <option key={plan} value={plan}>
                        {plan}
                      </option>
                    ))}
                </S.Select>
              ) : (
                <S.Text>{subscription.ott?.ratePlan}</S.Text>
              )}
            </S.Section>
            <S.Divider />
            <S.Section>
              <S.Label>결제 금액</S.Label>
              {editing ? (
                <S.Input
                  name="payment"
                  value={formData.payment}
                  onChange={handleChange}
                />
              ) : (
                <S.Text>{subscription.payment}원</S.Text>
              )}
            </S.Section>
            <S.Divider />
            <S.Section>
              <S.Label>정기결제일</S.Label>
              {editing ? (
                <S.Select
                  name="paymentDate"
                  value={formData.paymentDate.toString()}
                  onChange={handleChange}
                >
                  {dateOptions.map((date) => (
                    <option key={date} value={date}>
                      {`${date}일`}
                    </option>
                  ))}
                </S.Select>
              ) : (
                <S.Text>{`매월 ${subscription.paymentDate}일`}</S.Text>
              )}
            </S.Section>
            <S.Divider />
            <S.LabelMemo>메모</S.LabelMemo>
            {editing ? (
              <S.MemoBox>
                <S.InputMemo
                  name="memo"
                  value={formData.memo}
                  onChange={handleChange}
                />
              </S.MemoBox>
            ) : (
              <S.MemoBox>
                <S.TextMemo>{subscription.memo}</S.TextMemo>
              </S.MemoBox>
            )}
            <S.ButtonContainer>
              {editing ? (
                <S.ButtonSave onClick={handleSave}>저장하기</S.ButtonSave>
              ) : (
                <S.Button onClick={() => setEditing(true)}>수정하기</S.Button>
              )}
              {!editing && <S.Button onClick={handleDelete}>삭제하기</S.Button>}
            </S.ButtonContainer>
          </>
        )}
      </S.Container>
    </S.OttDetailWrapper>
  );
};

export default SubscriptionDetail;
            </pre>
          </div>
        </details>
      </td>
    </tr>
  </tbody>
</table>

<table>
  <tbody>
    <tr>
      <td colspan="4"  align="center">BE</td>
    </tr>
    <tr>
      <td rowspan="2">박세은</td>
      <td>
        <img src="" /><br/>
        <details>
          <summary>설명</summary>
          <div markdown="1">
          </div>
        </details>
      </td>
      <td rowspan="2">박소정</td>
      <td>
        <strong>이미지 호스팅</strong><br/>
        <img src="" /><br/>
        <details>
          <summary>설명</summary>
          <div markdown="1">
            - 이미지 호스팅으로 Amazon S3 버킷을 이용함.<br/>
            - 이미지를 생성하는 과정에서 저장명이 겹치면 안되기 때문에<br/>
            이미지 이름을 넣으면 랜덤으로 UUID로 변하는 changImageName() 메서드를 구현함.<br/>
            - 이미지 파일을 MultipartFile 타입으로 호스팅 요청을 받으면 post 폴더에 저장됨.<br/>
            - 사용자가 이미지 호스팅 한 글을 작성 중단한 경우, 사용되지 않는 이미지가 버킷에 계속 남게 됨.<br/>
            이런 이미지는 자원을 낭비하므로 특정 시각에 주기적으로 불필요한 이미지가 삭제되게 구현함.<br/>
            Post와 연결되지 않은 글 중에서 생성된 지 24시간이 지난 글은 버킷과 이미지 레포지토리에서 삭제됨.
          </div>
        </details>
      </td>
    </tr>
    <tr>
      <td>
        상세 코드
        <details>
          <summary>설명</summary>
          <div markdown="1">
          </div>
        </details>
      </td>
      <td>
        상세 코드
        <details>
          <summary>필드와 생성자</summary>
          <div markdown="1">
<pre>
  
private final AmazonS3 amazonS3;
private final ImageRepository imageRepository;
private final String bucket;

public ImageService(AmazonS3 amazonS3, ImageRepository imageRepository,@Value("${cloud.aws.s3.bucket}") String bucket) {
  this.amazonS3 = amazonS3;
  this.imageRepository = imageRepository;
  this.bucket = bucket;
}
  
</pre>
          </div>
        </details>
        <details>
          <summary>이미지 저장 요청 DTO</summary>
          <div markdown="1">
<pre> 
  @Getter
  public class UploadImageRequestDto {
    private MultipartFile image;
    public UploadImageRequestDto(MultipartFile image) {
        this.image = image;
    }
}
</pre>
          </div>
        </details>
        <details>
          <summary>private 메서드</summary>
          <div markdown="1">
<pre>
  
    private String uploadImage(final MultipartFile image,
                               final String ext,
                               final String changedImageName) throws IOException {
        final ObjectMetadata metadata = new ObjectMetadata();
        metadata.setContentType("image/" + ext.substring(1));
        try {
            amazonS3.putObject(new PutObjectRequest(
                    bucket, changedImageName, image.getInputStream(), metadata)
                    .withCannedAcl(CannedAccessControlList.PublicRead));
        } catch (final IOException e) {
            throw e;
        }
        return amazonS3.getUrl(bucket, changedImageName).toString();
    }
    private String changeImageName(final String ext) {
        final String uuid = UUID.randomUUID().toString();
        return uuid + ext;
    }
    private void deletePostImage(String imageName) {
        String fullPath = "post/" + imageName;
        amazonS3.deleteObject(new DeleteObjectRequest(bucket, fullPath));
    }
  
</pre>
          </div>
        </details>
        <details>
          <summary>public 메서드-이미지 저장</summary>
          <div markdown="1">
<pre>
  
    @Transactional
    public ImageResponseDto savePostImage(final UploadImageRequestDto requestDto) throws IOException {
        final String originName = requestDto.getImage().getOriginalFilename();
        final String ext = originName.substring(originName.lastIndexOf("."));
        final String changedImageName = changeImageName(ext);
        
        final String storeImagePath = uploadImage(requestDto.getImage(), ext, "post/" + changedImageName);
  
        Image image = Image.builder()
                .imageName(changedImageName)
                .imageUrl(storeImagePath)
                .build();
        imageRepository.save(image);
        return new ImageResponseDto(image.getId(), image.getImageUrl());
    }
    
</pre>
          </div>
        </details>
        <details>
          <summary>public 메서드-불필요한 메시지 삭제</summary>
          <div markdown="1">
<pre>
  
    @Scheduled(cron = "${cloud.aws.cron}")
    @Transactional
    public void deleteUnNecessaryImage() {

        List<Image> images = imageRepository.findAllByPostIsNull();

        images.stream()
                .filter(image -> new LocalDateTime(image.getCreatedDate()).plusHours(24).isBefore(LocalDateTime.now()))
                .forEach(image -> {
                    deletePostImage(image.getImageName());
                    imageRepository.delete(image);
                });
    }
</pre>
          </div>
        </details>
      </td>
    </tr>
  </tbody>
</table>

---

## ⏩ 프로젝트 확장성

<table>
  <thead>
    <tr>
      <th>🛠️ 기술 측면</th>
      <th>💁‍♀️ 서비스 측면</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1. 댓글 수정 기능</td>
      <td>1. 배지 기능</td>
    </tr>
    <tr>
      <td>2. 팟 해지(퇴장) 기능</td>
      <td>2. OTT 종류 추가</td>
    </tr>
    <tr>
      <td>3. 팟 정보 수정 기능</td>
      <td>3. 본인 인증(PASS 앱 등)</td>
    </tr>
    <tr>
      <td>4. 팟 본인 인증 강화(인증 시 아이디, 비번, 계좌 확인)</td>
      <td>4. 팟 채팅 기능</td>
    </tr>
    <tr>
      <td>5. 프로필 기본 이미지 변경 기능</td>
      <td></td>
    </tr>
    <tr>
      <td>6. 로그아웃, 탈퇴 기능</td>
      <td></td>
    </tr>
    <tr>
      <td>7. 알림 기능</td>
      <td></td>
    </tr>
    <tr>
      <td>8. 로딩 페이지 디자인 수정 및 필요한 페이지 삽입</td>
      <td></td>
    </tr>
    <tr>
      <td>9. 팟 삭제 기능</td>
      <td></td>
    </tr>
  </tbody>
</table>

<hr/>
</div>

## 😏 Team of Hoodie

<table>
<thead>
  <tr>
    <th colspan="2">Frontend</th>
    <th colspan="2">Backend</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td align="center">김주하</td>
    <td align="center">박예은</td>
    <td align="center">박세은</td>
    <td align="center">박소정</td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/laketree2">
        <img src="https://avatars.githubusercontent.com/u/101048129?v=4" style="width:230px"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/yengniws">
        <img src="https://avatars.githubusercontent.com/u/145003970?v=4" style="width:230px"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/seun123">
        <img src="https://avatars.githubusercontent.com/u/101261562?v=4" style="width:230px"/>
      </a>
    </td>
    <td>
      <a href="https://github.com/sojeong0202">
        <img src="https://avatars.githubusercontent.com/u/112674378?v=4" style="width:230px"/>
      </a>
    </td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/laketree2">@laketree2</a></td>
    <td align="center"><a href="https://github.com/yengniws">@yengniws</a></td>
    <td align="center"><a href="https://github.com/seun123">@seun123</a></td>
    <td align="center"><a href="https://github.com/sojeong0202">@sojeong0202</a></td>
  </tr>
</tbody>
</table>
