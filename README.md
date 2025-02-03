# Med-o-Next : Here Every Sickness Is A Myth :hospital:

## Problem Statement :dart:

In today’s fast-paced world, managing health for oneself or family can become overwhelming. From booking appointments to understanding prescriptions, patients often struggle to juggle multiple platforms for their healthcare needs. There is a need for a unified solution that simplifies healthcare access, empowers patients with knowledge, and integrates intelligent technologies to improve well-being.

## Our Initiative :bulb:

Introducing MED-O-NEXT, a groundbreaking all-in-one medical web app designed to cater to every healthcare need in one place. Imagine booking doctor appointments with ease, engaging in live video consultations, and ordering prescribed medications all through a single platform. But that’s just the beginning! Our app also provides a lab-test booking service where users can schedule essential diagnostic tests from nearby facilities. With a unique media service, users stay updated with the latest health news, trends, and medical breakthroughs, promoting awareness in an ever-evolving healthcare landscape.

## Key Features :key:

- **Med-o-Chat**: :speech_balloon:

  - Real-time medical consultations with certified doctors.
  - Schedule video consultations for in-depth discussions.
  - Share images and reports during chat for precise medical advice.
  - _New!_ Message history for better follow-up and patient-doctor communication.

- **Med-o-Shop**: :shopping_cart:

  - Directly order authentic medications from certified manufacturers.
  - Automatic refill reminders based on prescriptions.
  - Transparent pricing and home delivery options available for every user.
  - Discounted rates for long-term prescriptions and bulk orders.

- **Med-o-Lens**: :mag:

  - Upload and digitize medical reports and prescriptions with AI-powered OCR.
  - Easily access and organize reports, prescriptions, and doctor notes in one place.
  - Share medical reports instantly with your doctor or healthcare provider.

- **Med-o-AI**: :robot:

  - Get instant answers to medical queries with our AI-driven assistant.
  - Extensive knowledge base for reliable and accurate medical information.
  - Personalize the AI responses based on user’s health history and preferences.

- **Med-o-Coach**: :weight_lifting:
  - Personalized health coaching tailored to user’s medical history.
  - Smart reminders for medication, lab tests, and routine check-ups.
  - AI-powered health tips, exercise routines, and mental wellness guidance.

## Special Attributes :sparkles:

- **Multi-Language Support**: :earth_africa:
  - Supports over 20 global languages, enabling accessibility for users across the world.
  - Automatically detects the user's preferred language based on browser settings.
  - Option for manual selection of language with seamless transition across all app features.
- **Accessibility-First Design**: :wheelchair:
  - Fully compatible with assistive technologies like screen readers (NVDA, JAWS).
  - High-contrast themes and font size adjustment for users with visual impairments.
  - Voice command capabilities for users with limited mobility.

- **User-Centric Experience**: :busts_in_silhouette:

  - Designed with simplicity and ease-of-use in mind for both tech-savvy and non-tech users.
  - Intuitive navigation with quick access to key features like appointments, reports, and orders.
  - Responsive design ensuring a consistent experience across mobile, tablet, and desktop.

- **Data Privacy & Security**: :lock:
  - End-to-end encryption for all sensitive health data.
  - GDPR and HIPAA compliant, ensuring that user data is secure and confidential.
  - Multi-factor authentication and role-based access control for added security.

## Tech Stack :computer:

- **_Frontend_** :computer:
  <br/>
  ![](https://skillicons.dev/icons?i=js,html,tailwind,vite,next,python)

- **_Backend_** :computer:
  <br />
  ![](https://skillicons.dev/icons?i=nodejs,express,mongodb,firebase)

- **_DevOps_** :computer:
  <br />
  ![](https://skillicons.dev/icons?i=docker,vercel,kubernetes)

- **_Version Control_** :computer:
  <br />
  ![](https://skillicons.dev/icons?i=git,github)

- **_Code Editor_** :computer:
  <br />
  ![](https://skillicons.dev/icons?i=vscode)

## Our Team :busts_in_silhouette:

- **_Team Name_** : **Tech Janta Party**

&nbsp;

- **_Team Members_** :
   <table>
<tr>
  <td align="center">
   <a href="https://github.com/Sayambar2004/">
    <img style="height: 80px; width:80px;" src="https://avatars.githubusercontent.com/Sayambar2004"/><br />
    <sub><b>Sayambar RC</b></sub>
   </a>
 </td>
  <td align="center">
   <a href="https://github.com/Megh2005/">
    <img style="height: 80px; width:80px;" src="https://avatars.githubusercontent.com/Megh2005"/><br />
    <sub><b>Megh Deb</b></sub>
   </a>
 </td>
  <td align="center">
   <a href="https://github.com/iSubhamMani/">
    <img style="height: 80px; width:80px;" src="https://avatars.githubusercontent.com/iSubhamMani"/><br />
    <sub><b>Subham Mani</b></sub>
   </a>
 </td>
  <td align="center">
   <a href="https://github.com/rbose3">
    <img style="height: 80px; width:80px;" src="https://avatars.githubusercontent.com/rbose3"/><br />
    <sub><b>Ronit Bose</b></sub>
   </a>
 </td>
</tr>
</table>

## Folder Structure
```plaintext
Directory structure:
└── megh2005-med-o-next-hackathon/
    ├── README.md
    ├── CODE_OF_CONDUCT.md
    ├── CONTRIBUTING.md
    ├── LICENSE.md
    ├── SECURITY.md
    ├── med-o-ai/
    │   ├── README.md
    │   ├── components.json
    │   ├── next.config.ts
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.mjs
    │   ├── tailwind.config.ts
    │   ├── tsconfig.json
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── public/
    │   └── src/
    │       ├── middleware.ts
    │       ├── app/
    │       │   ├── Providers.tsx
    │       │   ├── globals.css
    │       │   ├── layout.tsx
    │       │   ├── page.tsx
    │       │   ├── api/
    │       │   │   ├── auth/
    │       │   │   │   └── [...nextauth]/
    │       │   │   │       └── route.ts
    │       │   │   ├── coach/
    │       │   │   │   └── route.ts
    │       │   │   ├── lens/
    │       │   │   │   └── route.ts
    │       │   │   ├── prescription/
    │       │   │   │   └── [id]/
    │       │   │   │       └── route.ts
    │       │   │   └── recommendation/
    │       │   │       └── [id]/
    │       │   │           └── route.ts
    │       │   ├── fonts/
    │       │   │   ├── GeistMonoVF.woff
    │       │   │   └── GeistVF.woff
    │       │   └── u/
    │       │       ├── layout.tsx
    │       │       ├── coach/
    │       │       │   └── page.tsx
    │       │       ├── home/
    │       │       │   └── page.tsx
    │       │       ├── lens/
    │       │       │   └── page.tsx
    │       │       ├── prescription/
    │       │       │   └── [id]/
    │       │       │       └── page.tsx
    │       │       ├── prescriptions/
    │       │       │   └── page.tsx
    │       │       ├── recommendation/
    │       │       │   └── [id]/
    │       │       │       └── page.tsx
    │       │       └── recommendations/
    │       │           └── page.tsx
    │       ├── components/
    │       │   ├── ErrorCard.tsx
    │       │   ├── HomeTopbar.tsx
    │       │   ├── ImageShimmer.tsx
    │       │   ├── PrescriptionCard.tsx
    │       │   ├── PrescriptionDetailsShimmer.tsx
    │       │   ├── PrescriptionShimmer.tsx
    │       │   ├── PrescriptionsList.tsx
    │       │   ├── RecommendationCard.tsx
    │       │   ├── RecommendationDetailsShimmer.tsx
    │       │   ├── RecommendationList.tsx
    │       │   ├── RecommendationShimmer.tsx
    │       │   ├── TextShimmer.tsx
    │       │   └── ui/
    │       │       ├── background-beams.tsx
    │       │       ├── background-gradient-animation.tsx
    │       │       ├── card-hover-effect.tsx
    │       │       ├── file-upload.tsx
    │       │       ├── flip-words.tsx
    │       │       ├── floating-dock.tsx
    │       │       └── text-generate-effect.tsx
    │       ├── hooks/
    │       │   └── use-outside-click.ts
    │       ├── interfaces/
    │       │   ├── HealthRecommendation.ts
    │       │   ├── Prescription.ts
    │       │   └── User.ts
    │       ├── lib/
    │       │   ├── auth.ts
    │       │   ├── db.ts
    │       │   ├── utils.ts
    │       │   └── cloudinary/
    │       │       ├── config.ts
    │       │       └── uploadToCloudinary.ts
    │       ├── models/
    │       │   ├── HealthRecommendation.ts
    │       │   ├── Prescription.ts
    │       │   └── User.ts
    │       ├── types/
    │       │   ├── next-auth.d.ts
    │       │   └── tailwindcss-flattenColorPalette.d.ts
    │       └── utils/
    │           └── ApiResponse.ts
    ├── med-o-chat/
    │   ├── README.md
    │   ├── components.json
    │   ├── next.config.mjs
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.mjs
    │   ├── tailwind.config.ts
    │   ├── tsconfig.json
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── public/
    │   └── src/
    │       ├── middleware.ts
    │       ├── app/
    │       │   ├── AuthProvider.tsx
    │       │   ├── StoreProvider.tsx
    │       │   ├── globals.css
    │       │   ├── layout.tsx
    │       │   ├── page.tsx
    │       │   ├── api/
    │       │   │   ├── accept-invitation/
    │       │   │   │   └── route.ts
    │       │   │   ├── all-messages/
    │       │   │   │   └── [chatId]/
    │       │   │   │       └── route.ts
    │       │   │   ├── cancel-invitation/
    │       │   │   │   └── route.ts
    │       │   │   ├── chat-details/
    │       │   │   │   └── [chatId]/
    │       │   │   │       └── route.ts
    │       │   │   ├── check-invitation/
    │       │   │   │   └── route.ts
    │       │   │   ├── conversations/
    │       │   │   │   └── route.ts
    │       │   │   ├── invitations/
    │       │   │   │   └── route.ts
    │       │   │   ├── login/
    │       │   │   │   └── route.ts
    │       │   │   ├── reject-invitation/
    │       │   │   │   └── route.ts
    │       │   │   ├── search/
    │       │   │   │   └── route.ts
    │       │   │   ├── send-message/
    │       │   │   │   └── route.ts
    │       │   │   └── update-lang-prefs/
    │       │   │       └── route.ts
    │       │   ├── chats/
    │       │   │   ├── page.tsx
    │       │   │   └── [chatId]/
    │       │   │       └── page.tsx
    │       │   └── login/
    │       │       └── page.tsx
    │       ├── components/
    │       │   ├── ChatInput.tsx
    │       │   ├── ChatLangPrefs.tsx
    │       │   ├── ChatMessage.tsx
    │       │   ├── ChatNavbar.tsx
    │       │   ├── ChatUser.tsx
    │       │   ├── ChatUserSkeleton.tsx
    │       │   ├── Conversations.tsx
    │       │   ├── CustomToast.tsx
    │       │   ├── InvitationBox.tsx
    │       │   ├── InvitationCard.tsx
    │       │   ├── InvitationCardSkeleton.tsx
    │       │   ├── Loader.tsx
    │       │   ├── MessagesContainer.tsx
    │       │   ├── Search.tsx
    │       │   ├── SearchedUser.tsx
    │       │   ├── SearchedUserSkeleton.tsx
    │       │   ├── UserInfo.tsx
    │       │   ├── UserInfoSkeleton.tsx
    │       │   └── ui/
    │       │       ├── alert-dialog.tsx
    │       │       ├── avatar.tsx
    │       │       ├── button.tsx
    │       │       ├── card.tsx
    │       │       ├── drawer.tsx
    │       │       ├── input.tsx
    │       │       ├── popover.tsx
    │       │       ├── scroll-area.tsx
    │       │       ├── select.tsx
    │       │       ├── separator.tsx
    │       │       ├── skeleton.tsx
    │       │       └── textarea.tsx
    │       ├── hooks/
    │       │   ├── useLangPrefsUpdate.tsx
    │       │   └── useNewMessage.tsx
    │       ├── interfaces/
    │       │   └── ConversationDetails.ts
    │       ├── lib/
    │       │   ├── constants.ts
    │       │   ├── db.ts
    │       │   ├── hooks.ts
    │       │   ├── pusher.ts
    │       │   ├── store.ts
    │       │   ├── utils.ts
    │       │   └── features/
    │       │       ├── conversationDetails/
    │       │       │   └── conversationDetailsSlice.ts
    │       │       ├── conversations/
    │       │       │   ├── conversationsConfigSlice.ts
    │       │       │   └── conversationsSlice.ts
    │       │       ├── invitation/
    │       │       │   ├── invitationConfigSlice.ts
    │       │       │   └── invitationSlice.ts
    │       │       └── user/
    │       │           ├── userConfig.ts
    │       │           └── userSlice.ts
    │       ├── models/
    │       │   ├── conversation.model.ts
    │       │   ├── invitation.model.ts
    │       │   ├── message.model.ts
    │       │   └── user.model.ts
    │       ├── services/
    │       │   └── firebase/
    │       │       └── config.ts
    │       ├── types/
    │       │   ├── InvitationRequest.ts
    │       │   ├── MessageRequest.ts
    │       │   ├── TranslationRequest.ts
    │       │   └── UserDetailsAndPrefs.ts
    │       └── utils/
    │           ├── ApiError.ts
    │           ├── ApiSuccess.ts
    │           ├── ConvertMongoDate.ts
    │           ├── CustomRequest.ts
    │           ├── convertDate.ts
    │           ├── encodeJWT.ts
    │           └── languages.ts
    ├── med-o-next-home/
    │   ├── README.md
    │   ├── components.json
    │   ├── next.config.mjs
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.mjs
    │   ├── tailwind.config.ts
    │   ├── tsconfig.json
    │   ├── .eslintrc.json
    │   ├── .gitignore
    │   ├── app/
    │   │   ├── globals.css
    │   │   ├── layout.tsx
    │   │   ├── page.tsx
    │   │   ├── about/
    │   │   │   └── page.tsx
    │   │   ├── apps/
    │   │   │   └── page.tsx
    │   │   ├── contact/
    │   │   │   └── page.tsx
    │   │   ├── fonts/
    │   │   │   ├── GeistMonoVF.woff
    │   │   │   └── GeistVF.woff
    │   │   └── team/
    │   │       └── page.tsx
    │   ├── components/
    │   │   ├── Footer.tsx
    │   │   └── ui/
    │   │       ├── animated-testimonials.tsx
    │   │       ├── card-hover-effect.tsx
    │   │       ├── floating-navbar.tsx
    │   │       ├── hero-highlight.tsx
    │   │       └── hero-parallax.tsx
    │   ├── lib/
    │   │   ├── utils.ts
    │   │   ├── actions/
    │   │   │   └── submitContactForm.ts
    │   │   └── db/
    │   │       └── index.ts
    │   └── models/
    │       └── Response.ts
    └── med-o-shop/
        ├── backend/
        │   ├── package-lock.json
        │   ├── package.json
        │   ├── tsconfig.json
        │   ├── .gitignore
        │   ├── public/
        │   │   └── uploads/
        │   │       └── .gitkeep
        │   └── src/
        │       ├── app.ts
        │       ├── index.ts
        │       ├── controllers/
        │       │   ├── address.controller.ts
        │       │   ├── admin.controller.ts
        │       │   ├── auth.controller.ts
        │       │   ├── cart.controller.ts
        │       │   ├── order.controller.ts
        │       │   ├── product.controller.ts
        │       │   └── search.controller.ts
        │       ├── db/
        │       │   └── index.ts
        │       ├── lib/
        │       │   ├── interfaces/
        │       │   │   ├── Address.ts
        │       │   │   ├── Cart.ts
        │       │   │   ├── CustomRequest.ts
        │       │   │   ├── Order.ts
        │       │   │   ├── Product.ts
        │       │   │   └── User.ts
        │       │   └── schemas/
        │       │       ├── address.schema.ts
        │       │       ├── product.schema.ts
        │       │       ├── signin.schema.ts
        │       │       └── signup.schema.ts
        │       ├── middlewares/
        │       │   ├── auth.middleware.ts
        │       │   └── multer.middleware.ts
        │       ├── models/
        │       │   ├── address.model.ts
        │       │   ├── cart.model.ts
        │       │   ├── order.model.ts
        │       │   ├── product.model.ts
        │       │   └── user.model.ts
        │       ├── routes/
        │       │   ├── address.route.ts
        │       │   ├── admin.route.ts
        │       │   ├── auth.route.ts
        │       │   ├── cart.route.ts
        │       │   ├── mainRouter.ts
        │       │   ├── order.route.ts
        │       │   ├── product.route.ts
        │       │   └── search.route.ts
        │       └── utils/
        │           ├── ApiResponse.ts
        │           ├── asyncHandler.ts
        │           ├── cloudinary.ts
        │           ├── constants.ts
        │           ├── errorHandler.ts
        │           └── getCloudinaryId.ts
        └── frontend/
            ├── README.md
            ├── components.json
            ├── eslint.config.js
            ├── index.html
            ├── package-lock.json
            ├── package.json
            ├── postcss.config.js
            ├── tailwind.config.js
            ├── tsconfig.app.json
            ├── tsconfig.json
            ├── tsconfig.node.json
            ├── vite.config.ts
            ├── .gitignore
            ├── public/
            └── src/
                ├── App.tsx
                ├── index.css
                ├── main.tsx
                ├── vite-env.d.ts
                ├── assets/
                ├── components/
                │   ├── Address.tsx
                │   ├── CartItem.tsx
                │   ├── FilterBox.tsx
                │   ├── HeroSection.tsx
                │   ├── Navbar.tsx
                │   ├── ProductAdminItem.tsx
                │   ├── ProductManageForm.tsx
                │   ├── ProductSearchResult.tsx
                │   ├── SearchInput.tsx
                │   ├── SearchResults.tsx
                │   ├── SearchResultsSection.tsx
                │   ├── ShopByCategory.tsx
                │   └── ui/
                │       ├── button.tsx
                │       ├── calendar.tsx
                │       ├── card.tsx
                │       ├── carousel.tsx
                │       ├── checkbox.tsx
                │       ├── dialog.tsx
                │       ├── form.tsx
                │       ├── input.tsx
                │       ├── label.tsx
                │       ├── popover.tsx
                │       ├── radio-group.tsx
                │       ├── select.tsx
                │       ├── separator.tsx
                │       └── textarea.tsx
                ├── lib/
                │   ├── utils.ts
                │   ├── interfaces/
                │   │   ├── Address.ts
                │   │   ├── Cart.ts
                │   │   ├── Order.ts
                │   │   ├── Product.ts
                │   │   └── RootState.ts
                │   ├── redux/
                │   │   ├── appStore.ts
                │   │   └── slices/
                │   │       ├── cartSlice.ts
                │   │       ├── filterSlice.ts
                │   │       └── searchSlice.ts
                │   └── schemas/
                │       ├── address.schema.ts
                │       ├── filter.schema.ts
                │       ├── product.schema.ts
                │       ├── signin.schema.ts
                │       └── signup.schema.ts
                ├── pages/
                │   ├── AddProduct.tsx
                │   ├── Admin.tsx
                │   ├── AdminRoot.tsx
                │   ├── BillingAddress.tsx
                │   ├── Cart.tsx
                │   ├── Home.tsx
                │   ├── OrderFailure.tsx
                │   ├── OrderSuccessfull.tsx
                │   ├── PlaceOrder.tsx
                │   ├── ProductDetails.tsx
                │   ├── SearchPage.tsx
                │   ├── SignIn.tsx
                │   ├── Signup.tsx
                │   ├── UpdateProduct.tsx
                │   ├── UserHome.tsx
                │   └── UserRoot.tsx
                └── utils/
                    ├── constants.ts
                    └── searchRequest.ts
```
